# Desafio Controle de Fluxo - Java

## Descrição

Este projeto é uma implementação prática do módulo de Controle de Fluxo do curso de Java da [DIO](https://www.dio.me). O objetivo do desafio é criar um programa que receba dois números inteiros via terminal e imprima uma série de mensagens baseadas nesses números. Se o primeiro número for maior que o segundo, o programa deve lançar uma exceção personalizada.

## Autor
Wallace Tadeu da Silva

## Funcionalidades

- Recebe dois números inteiros do usuário.
- Imprime todos os números no intervalo entre os dois parâmetros, incluindo os próprios parâmetros.
- Lança uma exceção personalizada se o primeiro parâmetro for maior que o segundo.

## Requisitos

- **Java 8** ou superior.
- Um editor de texto ou IDE que suporte Java (por exemplo, IntelliJ IDEA, VS Code).

## Uso
Digite o primeiro parâmetro: O menor número do intervalo.
Digite o segundo parâmetro: O maior número do intervalo.
Observe a saída: O programa imprimirá todos os números entre os dois parâmetros em ordem crescente. Caso o primeiro número seja maior que o segundo, será exibida uma mensagem de erro.
Exemplo de Saída
Se você inserir 12 como o primeiro parâmetro e 30 como o segundo, a saída será:

sh
Copiar código
Digite o primeiro parâmetro
12
Digite o segundo parâmetro
30
Imprimindo o número 12
Imprimindo o número 13
Imprimindo o número 14
...
Imprimindo o número 30
Se o primeiro parâmetro for maior que o segundo, o programa exibirá:

sh
Copiar código
O segundo parâmetro deve ser maior que o primeiro
