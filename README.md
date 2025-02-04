# Teste Prático - Sistema de Gerenciamento de Funcionários

Este é um projeto Java simples que demonstra operações básicas de gerenciamento de funcionários.

## Requisitos

- Java 11 ou superior

## Como executar

1. Clone o repositório
2. Navegue até a pasta do projeto
3. Compile e execute o projeto usando sua IDE favorita ou via linha de comando:

```bash
javac src/main/java/model/*.java src/main/java/Principal.java
java -cp src/main/java Principal
```

## Funcionalidades

O programa implementa as seguintes funcionalidades:

1. Cadastro de funcionários
2. Remoção de funcionário específico
3. Listagem de funcionários com formatação específica
4. Aumento de salário
5. Agrupamento por função
6. Listagem de aniversariantes de outubro e dezembro
7. Identificação do funcionário mais velho
8. Ordenação alfabética
9. Cálculo do total de salários
10. Cálculo de salários mínimos por funcionário

## Estrutura do Projeto

- `src/main/java/model/Pessoa.java`: Classe base com atributos básicos
- `src/main/java/model/Funcionario.java`: Classe que estende Pessoa com atributos específicos
- `src/main/java/Principal.java`: Classe principal com a lógica de negócio 