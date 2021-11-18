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

`v-on` é o evento que vai ser executado quando o usuário clicar no elemento.

Para usar eventos no Vue não precisa utilizar a palavra `v-on`, pode-se utilizar somente `@nome_do_evento`

Para chamar um método, é necessário utilizar a palavra `@nome_do_evento="nomeDoMetodo"`

Se o método receber algum parâmetro, é necessário utilizar a palavra => `:nome_do_evento="nomeDoMetodo(conteúdoDoParametro)"`

## Components

Um componente precisa ter uma tag `template:` onde ficará a estrutura desse componente. E também uma função `data(){}` onde irá ficar as ações do componente.

para criar um componente usa-se:

```ts
app.component('nome-do-compnente', {
// Conteúdo do componente.
  template: ``,

  data() {
    return {
      // Conteúdo da função data.
    }
  }

})
```
