# Sistema de Gerenciamento de Funcionários

Sistema simples em Java para gerenciamento de funcionários, incluindo operações de cadastro, remoção, listagem e cálculos salariais.

## Requisitos

- Java 11 ou superior

## Como executar

1. Clone o repositório:
```bash
git clone https://github.com/gotiquinha/iniflex.git
```

2. Entre na pasta do projeto:
```bash
cd [NOME_DO_REPOSITORIO]
```

3. Compile os arquivos:
```bash
javac Principal.java Funcionario.java Pessoa.java
```

4. Execute o programa:
```bash
java Principal
```

## Funcionalidades

O programa implementa as seguintes funcionalidades:

1. Cadastro de funcionários
2. Remoção de funcionário específico
3. Listagem de funcionários com formatação específica (data: dd/mm/aaaa, valor numérico com separadores)
4. Aumento de 10% nos salários
5. Agrupamento por função
6. Listagem de aniversariantes de outubro e dezembro
7. Identificação do funcionário mais velho
8. Ordenação alfabética
9. Cálculo do total dos salários
10. Cálculo de salários mínimos por funcionário

## Estrutura do Projeto

- `Pessoa.java`: Classe base com atributos nome e data de nascimento
- `Funcionario.java`: Classe que estende Pessoa, com atributos salário e função
- `Principal.java`: Classe principal com a lógica de negócio 
