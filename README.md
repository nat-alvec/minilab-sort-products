![logo_ironhack_blue 7](https://user-images.githubusercontent.com/23629340/40541063-a07a0a8a-601a-11e8-91b5-2f13e4e6b441.png)

# MINILAB | Filtrar Lista de Produtos

Nesse minilab vamos praticar loops, acesso à propriedades de objetos, condicionais e declaração de funções

## Requerimentos

- Faça um fork deste repositório
- Clone este repositório

## Instruções 

Considere a seguinte array, representando um conjunto de produtos:

```javascript
const products = [
  {
    id: 1,
    name: 'Iphone 11',
    tags: ['smartphone', 'tech', 'apple']
  },
    {
    id: 2,
    name: 'Macbook Pro',
    tags: ['laptop', 'tech', 'apple']
  },
    {
    id: 3,
    name: 'JBL Headphones',
    tags: ['headphone', 'tech', 'jbl']
  },
    {
    id: 4,
    name: 'Nike Shorts',
    tags: ['shorts', 'clothing', 'nike']
  },
]
```

Escreva uma função `filterProducts` que recebe como  único parâmetro uma string `category`, e usando esta informação, retorne uma nova array desta função, que inclua apenas os objetos dos produtos cuja propriedade 
`category` inclua o argumento passado. Exemplo:

Chamando a função com o seguinte argumento

```javascript
filterProducts('apple')
```

O resultado deve ser:

```javascript
// Array somente com os produtos da Apple
[
  {
    id: 1,
    name: 'Iphone 11',
    tags: ['smartphone', 'tech', 'apple']
  },
    {
    id: 2,
    name: 'Macbook Pro',
    tags: ['laptop', 'tech', 'apple']
  }
]
```

Utilize alguma ferramenta como o RunJS ou [REPL.it](https://replit.com/) para testar seu código e quando tiver certeza que o código está correto, copie e cole no arquivo `index.js`.

Quando terminar, copie e cole o link do seu repositório (basta copiar a URL atual do seu navegador) na unidade deste exercício no Student Portal (my.ironhack).
