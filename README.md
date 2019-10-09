# Back-end Challenge - Doc88

A necessidade é desenvolver uma API RESTFul para o gerenciamento de pedidos de uma pastelaria utilizando o framework Laravel/Lúmen.

## Instruções para entrega

* Versione, com git, e hospede seu código em algum serviço de sua preferência: github, bitbucket, gitlab ou outro.
* Crie um README com instruções claras sobre como executar sua obra.
* Envie um email com o link do seu repositório para fernando.dias@doc88.com.br
* Dúvidas podem ser enviadas para o mesmo email acima.

## Sobre o projeto

A API deve contemplar os módulos **Cliente**, **Pastel** e **Pedido**, sendo que cada um devera conter os seguintes endpoints (CRUDL), exemplo:

* `[POST] /api/clientes/` Cadastrar novo cliente;
* `[GET] /api/clientes/${id}` Ler dados de cliente via ID;
* `[GET] /api/clientes/` Listar Ler todos os clientes;
* `[UPDATE] /api/clientes/${id}` Atualizar dados de cliente via ID;
* `[DELETE] /api/clientes/${id}` Deletar cliente via ID;

As tabelas devem conter as seguintes informações:

* **Cliente** `nome, email, telefone, data de nascimento, endereço, complemento, bairro, cep, data de cadastro`;
* **Pastel** `nome, preço, foto`;
* **Pedido** `código do cliente, código(s) do pastel, data da criação`;

## Requisitos

* Não devem existir dois clientes com o mesmo email.
* O pastel deve possuir foto.
* Os dados devem ser validados.
* O sistema deve conter uma série de tipos de pastéis já definidos.
* O pedido deve contemplar N pastéis.
* O cliente pode contemplar N pedidos.
* Após a criação do pedido o sistema deve disparar um email para o cliente contendo os detalhes do seu pedido.
* Os registros devem conter a funcionalidade de soft deleting.

## Requisitos opcionais

* Testes unitários.
* Estrutura para subir a aplicação criada (Dockerfile)
* Endpoint de relacionamento, exemplo `api/cliente/pedidos/`
* Endpoint de filtro, exemplo `api/cliente/perpage/active?page=1&cliente_id=10`

## Critérios de avaliação

* Profundidade do conhecimento e utilização das funcionalidades do framework.
* Organização do código.
* Fidelidade aos requisitos solicitados.
