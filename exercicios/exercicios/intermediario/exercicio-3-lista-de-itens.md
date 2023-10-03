# Exercício 3 - (Lista de itens)

### <mark style="color:blue;">Descrição do exercício:</mark>

***

&#x20;**Criar uma lista de itens que seja possível filtrar o elemento pesquisado.**

{% embed url="https://codesandbox.io/s/lista-de-itens-rf52dw?file=/src/App.js" %}
Exercício: lista de itens
{% endembed %}

### <mark style="color:blue;">Explicação:</mark>

***

**Este exercício utiliza o hook `useState` para gerenciar o estado de `searchTerm` e `items`.**

**`useState` é um hook do React que permite adicionar estado a um componente de função. Ele retorna um par de valores: o estado atual e uma função para atualizar o estado.**

**No início do componente, `searchTerm` e `items` são inicializados usando o `useState` com valores vazios para `searchTerm` e uma lista de itens para `items`. O `searchTerm` é usado para filtrar a lista de itens com base no nome do item usando a função `filter`.**

**A função `handleSearch` é chamada sempre que o usuário digita algo na barra de pesquisa, atualizando o valor de `searchTerm` com o valor digitado pelo usuário.**

**A lista de itens é renderizada na tela usando o método `map`, que cria uma lista de elementos `li` para cada item na lista de itens filtrada. Cada elemento `li` contém informações sobre o item, como título, detalhes e imagem.**

