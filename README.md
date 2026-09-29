# Cadastro de Produtos

## Sobre o projeto

Este projeto é uma página simples para cadastrar produtos utilizando **HTML, PHP e SQLite**.

O usuário informa o nome e o preço do produto. O sistema verifica se os dados foram preenchidos corretamente e, caso estejam válidos, salva o produto em um banco de dados SQLite.

## Como funciona

O formulário possui dois campos:

- **Nome do Produto:** campo para informar o nome do produto.
- **Preço:** campo para informar o preço do produto.

Depois de preencher os campos, basta clicar no botão **Cadastrar**.

## Validações

O sistema realiza algumas validações antes de cadastrar o produto:

- Verifica se o nome do produto não está vazio.
- Verifica se o preço é um número.
- Verifica se o preço é maior que zero.

Caso algum dado esteja incorreto, uma mensagem de erro é exibida.

Quando o cadastro é realizado corretamente, aparece a mensagem:

**Produto cadastrado com sucesso!**

A mensagem desaparece automaticamente depois de 5 segundos.

## Banco de dados

O projeto utiliza o **SQLite**, que cria automaticamente o arquivo `exercicio.db` na mesma pasta do código.

A tabela utilizada é chamada `produtos` e possui os seguintes campos:

- `id`: identificador do produto.
- `nome`: nome do produto.
- `preco`: preço do produto.

A tabela é criada automaticamente caso ainda não exista.

## Tecnologias utilizadas

- HTML
- PHP
- SQLite
- JavaScript

## Objetivo

O objetivo do projeto é praticar a criação de um formulário em HTML, o recebimento e validação de dados com PHP e o armazenamento das informações em um banco de dados SQLite.