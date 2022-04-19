# Shopping Cart

Shopping Cart é uma página de compras onde há diversos produtos à venda, sendo possível adicioná-los ao seu carrinho de compras. O carrinho funciona de forma dinâmica, permitindo excluir os produtos que não forem mais do seu interesse ou esvaziá-lo por completo caso não queira mais realizar uma compra.

## Tecnologias utilizadas

Projeto desenvolvido utilizando HTML, CSS e JavaScript na construção da página, localStorage para armazenar os produtos no carrinho de compras, Jest nos testes unitários e a [API do Mercado Livre](https://developers.mercadolivre.com.br/pt_br/itens-e-buscas) para a obtenção de produtos à venda.

O conteúdo da pasta `mocks`, os arquivos `index.html` e `style.css` e as funções `createProductImageElement`, `createCustomElement`, `createProductItemElement`, `getSkuFromProductItem` e `createCartItemElement` do arquivo `script.js` foram fornecidas pela [Trybe](https://betrybe.com).

## Instalação das dependências

Você precisará de um ambiente de execução [Node.js](https://nodejs.org) instalado em sua máquina para executar o comando de instalação de dependências.

Com o repositório clonado e dentro de um terminal:

1. Entre na pasta do repositório:

```
cd project-shopping-cart/
```

2. Instale as dependências:

```
npm install
```

## Como executar a aplicação

Abra o arquivo `index.html` utilizando um navegador de sua preferência.

## Como executar os testes

Para executar todos os testes:

```
npm test
```

Para executar um teste específico, execute npm test com o caminho do arquivo de teste, por exemplo:

```
npm test tests/fetchItem.test.js
```

---
