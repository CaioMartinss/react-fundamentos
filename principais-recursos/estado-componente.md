# Estado(componente)

## <mark style="color:blue;">Estado(State)</mark>

***

&#x20;       **Em React, o estado(**_**state**_**) é uma propriedade que permite que um componente mantenha e gerencie informações ao longo do tempo. É uma forma de armazenar dados em um componente e, quando o estado é atualizado, o React re-renderiza o componente com as informações mais recentes.**

&#x20;           **O estado é um objeto JavaScript que contém propriedades e seus valores associados. Ele é inicializado no construtor do componente e pode ser atualizado usando o método `setState()`. Quando o estado é atualizado, o React re-renderiza o componente com as informações mais recentes.**

&#x20;         **O estado é uma das principais ferramentas que o React oferece para criar interfaces de usuário dinâmicas e interativas. Quando o estado de um componente é atualizado, o React pode atualizar a interface do usuário para refletir essas mudanças sem a necessidade de recarregar a página inteira.**

### <mark style="color:blue;">Exemplo:</mark>

***

{% embed url="https://codesandbox.io/s/state-estadp-ftmjgr?file=/src/App.js" %}
_State_(Estado)
{% endembed %}

### <mark style="color:blue;">Explicação:</mark>

***

**Nesse exemplo, usamos o **_**hook**_** `useState` para criar uma variável de estado chamada `count`, que começa com o valor `0`. O método `setCount` atualiza o valor do estado sempre que o botão é clicado.**

**O componente `Button` retorna um parágrafo que exibe o número de cliques atuais e um botão que chama a função `handleClick()` sempre que é clicado. A função `handleClick()` usa o método `setCount()` para atualizar o valor do estado `count` adicionando 1 ao valor atual.**

**Assim, toda vez que o botão é clicado, o estado é atualizado e a interface do usuário é re-renderizada com o novo valor de `count`.**
