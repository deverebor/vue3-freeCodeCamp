# Vue3 basic

## data

```js
data: {
  message: 'Hello Vue3!'
}
```

Tudo que estiver dentro do data será acessível em todos os componentes. Ou seja, todas as funções e variáveis que estiverem dentro do data serão acessíveis em todos os componentes.

```js
{{ message }}
```

Tudo que estiver entre as `{{}}` é a explicitação que ali vamos passar uma variável para o javascript. Ele procurará dentro do `data:{}` algo que possua esse nome e irá retornar.

## VueJs Directives

Para pegar o valor armazenado dentro e um input e alterar o seu estado, é necessário usar o `v-model`.

`v-cloak` esconde o elemento da tela até ser renderizado.

## Events & Methods

d
