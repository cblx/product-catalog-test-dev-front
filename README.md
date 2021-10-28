# Catálogo de produtos - Dev Front

## Contexto

A varejista Descontrolada® identificou que está perdendo o controle sobre os produtos que ela vende.

Sendo assim, a empresa deseja implementar um sistema para ter mais confiabilidade nos registros.

## Demanda

Criar e desenvolver a interface, e implementar o front de um sistema web com duas páginas, a saber:

1. Página para o cadastro dos produtos, que deve apresentar os campos: **nome, preço de venda, descrição, quantidade, tipo\* e data de validade**.
    - *A varejista comercializa dois tipos de produto:
        - Orgânico, e;
        - Não orgânico.

2. Página para exibição dos produtos cadastrados, que deverá mostrar apenas 5 itens por página (de uma grid/tabela).

3. Como o cliente quer manter a sua identidade corporativa no sistema, usar como referência gráfica o arquivo Adobe XD da landing page Descontrolada®: [clique aqui para baixar](https://github.com/cblx/product-catalog-test-ui-ux/raw/main/descontrolada.xd). Opção em PNG: [clique aqui](https://github.com/cblx/product-catalog-test-ui-ux/raw/main/des-home.png). As fontes usadas no layout (Abril Fat Face e Open Sans) estão disponíveis no [Google Fonts](https://fonts.google.com/).

O sistema também deve possuir um menu que permita a navegação entre as duas páginas.

## Tecnologia a ser utilizada

O *frontend* pode ser desenvolvido em [Vue.js](https://vuejs.org/) ou [Angular](https://angular.io/), priorizando sempre as versões mais recentes e que faça uso do [TypeScript](https://www.typescriptlang.org/).

O *backend* está disponibilizado no endereço [https://descontrolada-backend.cblx.com.br/swagger](https://descontrolada-backend.cblx.com.br/swagger). Ele está estruturado de modo que possui as seguintes funcionalidades:

- Listagem paginada dos produtos;
- Adição, atualização, remoção e visualização de um produto;

A empresa, com a finalidade de controlar os seus estoques **por loja**, decidiu utilizar o endereço de e-mail delas para distinguí-las.
Ou seja, você precisará escolher um e-mail arbitrário (exemplo: `um@emailqualquer.com`) no parâmetro `emailDaLoja` para realizar as chamadas dos métodos da API.

Para os campos configurados como `TipoDoProduto`, utilizar o valor numérico `1` para orgânicos e `2` para não orgânicos.

**Observação**: Os dados registrados são transientes, sendo eliminados de tempos em tempos.

## O que será avaliado no teste?

Serão avaliados os seguintes aspectos:

- Capacidade de abstração e desdobramento da identidade visual pré-existente;
- Conhecimento básico sobre REST API e métodos HTTP;
- Organização do código;
- Proeficiência nas tecnologias de frontend (Vue ou Angular);
- Conhecimento em TypeScript;

## Informações Adicionais 

Por favor, encaminhe o link do teste resolvido em um repositório GitHub para o e-mail [code-challenge@codeblox.com.br](mailto:code-challenge@codeblox.com.br).

Poderemos convidá-lo, em um segundo momento, para batermos um papo sobre a solução que você escreveu 😉.
