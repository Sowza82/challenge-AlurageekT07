# Challenge AluraGeekT07

Este é o projeto "Challenge AluraGeekT07", desenvolvido como parte da trilha de **Especificação Front-End** do curso ONE (Oracle + Alura). O projeto é um site de e-commerce que permite listar, criar e excluir produtos, utilizando o **JSON Server** como back-end simulado e **HTML, CSS, JavaScript** para o front-end.

## Sobre o Projeto

O objetivo deste projeto é construir uma aplicação de e-commerce simples, onde o usuário pode interagir com os produtos listados, adicionar novos produtos e excluir os existentes. A aplicação foi desenvolvida com foco em boas práticas de desenvolvimento Front-End, como a organização de código, interatividade e comunicação com o back-end via API REST.

## Tecnologias Utilizadas

- **HTML**: Estruturação da página.
- **CSS**: Estilização da interface.
- **JavaScript**: Interatividade da página e integração com a API.
- **JSON Server**: Simulação de uma API REST para persistência de dados.
- **Live Server**: Servidor local para visualização da aplicação no navegador.
- **npm-run-all**: Executa scripts de forma paralela.
  
  ## Como Usar

- Ao abrir o site no navegador, você verá a lista de produtos já cadastrados.
- Você pode adicionar novos produtos utilizando o formulário na página.
- Para excluir um produto, clique no ícone de lixeira ao lado do produto desejado.

## Como Funciona

1. **Adição de Produtos**: 
   - Ao preencher o formulário e enviar, um novo produto é criado via `POST` na API simulada (JSON Server).
   - O novo produto é renderizado dinamicamente na tela, sem necessidade de recarregar a página.

2. **Exclusão de Produtos**: 
   - Ao clicar no ícone de lixeira, o produto é excluído via `DELETE` na API simulada (JSON Server).
   - O produto é removido instantaneamente da interface, sem necessidade de recarregar a página.
