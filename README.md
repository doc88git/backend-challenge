# Back-end Challenge - Doc88

A necessidade é desenvolver uma API RESTFul para o gerenciamento de pedidos de uma **pastelaria** utilizando o framework Laravel/Lúmen.

## Instruções para entrega

* Versione, com git, e hospede seu código em algum serviço de sua preferência: github, bitbucket, gitlab ou outro.
* Crie um README com instruções claras sobre como executar sua obra.
* Envie um email com o link do seu repositório para cassio.santos@doc88.com.br
* Dúvidas podem ser enviadas para o mesmo email acima.

## Sobre o projeto

A API Restful deve contemplar os módulos **Cliente**, **Produto** e **Pedido**, sendo que cada um devera conter  endpoints **CRUDL**.

As tabelas devem conter as seguintes informações:

* **Clientes** `nome, email, telefone, data de nascimento, endereço, complemento, bairro, cep, data de cadastro`;
* **Produtos** `nome, preço, foto`;
* **Pedidos** `código do cliente, código do produto, data da criação`;

## Requisitos

* Não devem existir dois clientes com o mesmo email.
* O produto deve possuir foto.
* Os dados devem ser validados.
* O sistema deve conter uma série de tipos de produtos já definidos.
* O pedido deve contemplar N produtos.
* O cliente pode contemplar N pedidos.
* Após a criação do pedido o sistema deve disparar um email para o cliente contendo os detalhes do seu pedido.
* Os registros devem conter a funcionalidade de soft deleting.
* Padronização PSR
* Nomenclatura de classes, métodos e rotas no padrão americano.

## Requisitos adicionais

* Testes unitários.
* Dockerizar a aplicação

## Critérios de avaliação

* Profundidade do conhecimento e utilização das funcionalidades do framework.
* Organização do código.
* Padronização PSR
* Fidelidade aos requisitos solicitados.
