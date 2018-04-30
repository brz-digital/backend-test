# Teste para candidatos à vaga de backend

> <img src="https://raw.githubusercontent.com/brz-digital/backend-test/develop/brz.png" width="160" height="120" />
>
> Esse teste é público. Candidatos para o teste devem implementar a aplicação solicitada e criar uma issue com um link para um repositório com a solução do mesmo.

## Objetivo
Criar uma aplicação web que implemente um CRUD de imóveis. Um imóvel é uma casa, apartamento, terreno ou loja com as seguintes características:

### Imóvel:
> ** CRUD da entidade Imóvel:**
> - Id
> - Reference (Código do imóvel)
> - Type (Casa, Apartamento, Terreno, Loja)
> - Pretension (Venda, Aluguel)
> - Title
> - Details
> - Price
> - Bedrooms

> **Critérios de aceitação:**
> - Todos os atributos são obrigatórios.
> - ID não pode se repetir.
> - Deve ser possível pesquisar os imóveis por qualquer atributo, exceto pelo id.
> - Deve ser possível pesquisar os imóveis por faixa de preço.

### Interessados:
> **Permite incluir ou excluir interessados, sabendo que:**
> - Id
> - Cliente
> - Email

> **Um interessado pode ter um ou mais Interesses:**
> - Id
> - Cliente
> - Imóvel

> **Critérios de aceitação:**
> - Todos os atributos são obrigatórios.
> - ID e Email não podem se repetir.
> - Deve ser possível pesquisar os interessados por cliente, e-mail ou imóvel.

Não existe cadastro de usuários e/ou autenticação.

## Requisitos:
- A aplicação deve comportar-se como uma REST FULL Api.
- Backend desenvolvido em Laravel 5.5+
- Processo de desenvolvimento versionado via Git em algum repositório público.
- Readme que explique como rodar o projeto.
- A aplicação deve possuir um script que popula o banco inicialmente com imóveis, interessados e interesses fictícios para demonstração.

## Critérios de avaliação:
- Modelagem do banco de dados e das migrations.
- Organização do código: desacoplamento e legibilidade contam.
- Flexibilidade do sistema para adição/remoção de funcionalidades.

## Como vamos avaliar:
- Vamos rodar as migrations.
- Vamos subir a aplicação e cadastrar/editar/deletar algumas entidades. Vamos listar os imóveis segundo diferentes combinações de filtros.
- Vamos ler o código.

## O que nós gostamos:
- Arquitetura que favorece a escalabilidade do sistema.
- Ambientes de desenvolvimento em Docker, utilizando compose.
- Códigos escritos para humanos.
