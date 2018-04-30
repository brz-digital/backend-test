# Teste para candidatos à vaga de backend

> <img src="https://raw.githubusercontent.com/brz-digital/backend-test/develop/brz.png" width="80" height="60" />
>
> Esse teste é público. Candidatos devem implementar a aplicação solicitada e enviar o link do repositório para atendimento@brzdigital.com.br.

## Objetivo
Criar uma aplicação web que implemente um CRUD de imóveis. Um imóvel é uma casa, apartamento, terreno ou loja com as seguintes características:

### Imóvel:
> **O sistema deve permitir o cadastro/edição/exclusão de imóveis com as propriedades (código, tipo, pretensão, título, detalhes, quartos e valor).**

> **Critérios de aceitação:**
> - Todos os atributos são obrigatórios.
> - Código não pode se repetir.
> - Deve ser possível pesquisar os imóveis por qualquer atributo, exceto pelo id.
> - Deve ser possível pesquisar os imóveis por faixa de preço.

### Interessados:
> **O sistema deve permitir o cadastro/edição/exclusão de interessados com as propriedades (nome, email).**
> **Um interessado pode ter um ou mais Interesses com as propriedades (interessado, imóvel).**

> **Critérios de aceitação:**
> - Todos os atributos são obrigatórios.
> - Email não pode se repetir.
> - Deve ser possível pesquisar os interessados por nome, email ou imóvel.

Não existe cadastro de usuários e/ou autenticação.

## Requisitos:
- A aplicação deve comportar-se como uma REST FULL Api.
- Backend desenvolvido em Laravel 5.5+
- Processo de desenvolvimento versionado via Git em algum repositório público.
- Readme que explique como rodar o projeto.
- A aplicação deve possuir um script que popula o banco inicialmente com imóveis, interessados e interesses fictícios para demonstração.

## Critérios de avaliação:
- Modelagem do banco de dados e das migrations.
- Organização do código: desacoplamento e legibilidade.
- Flexibilidade do sistema para adição/remoção de funcionalidades.

## Como vamos avaliar:
- Vamos rodar as migrations.
- Vamos subir a aplicação e cadastrar/editar/deletar algumas entidades. Vamos listar os imóveis segundo diferentes combinações de filtros.

## Gostamos de:
- Arquitetura que favorece a escalabilidade do sistema.
- Ambientes de desenvolvimento em Docker.
- Códigos escritos para humanos.

Tudo que for desenvolvido não será utilizado comercialmente e a única intenção é de avaliar o conhecimento atual do interessado.