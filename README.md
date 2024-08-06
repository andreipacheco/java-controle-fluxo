# Desafio Controle de Fluxo 🚀

Este projeto consiste em um sistema que recebe dois números inteiros como parâmetros e realiza uma contagem com base nesses números. Se o primeiro número for maior que o segundo, uma exceção customizada será lançada.

## Estrutura do Projeto 📁
DesafioControleFluxo/
├── Contador.java
└── ParametrosInvalidosException.java

## Funcionalidade 📝
O sistema solicita ao usuário dois números inteiros:

Primeiro parâmetro: Representa o valor inicial.
Segundo parâmetro: Representa o valor final.
O sistema verifica se o segundo parâmetro é maior que o primeiro:

Se não for, lança a exceção ParametrosInvalidosException com a mensagem: "O segundo parâmetro deve ser maior que o primeiro".
O sistema realiza uma contagem do primeiro parâmetro até o segundo, imprimindo no console cada número incrementado:

Exemplo: Se os números forem 12 e 30, o sistema imprimirá 18 números no formato "Imprimindo o número X".

## Exemplo de Uso 💻

java Contador

Ao executar o programa, você verá as seguintes solicitações:

Digite o primeiro parâmetro
12
Digite o segundo parâmetro
30


Licença 📄
Este projeto está licenciado sob os termos da licença MIT.