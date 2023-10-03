# Exercício 1 - (Contador)

### <mark style="color:blue;">Descrição do exercício:</mark>

***

&#x20;**Crie um contador onde mostra o número de quantas vezes foi clicado, função de incrementar, decrementar e resetar o contador.**

{% embed url="https://codesandbox.io/s/contador-9qv8tm?file=/src/App.js" %}

### <mark style="color:blue;">Explicação:</mark> &#x20;

***

&#x20;       **Este exemplo de exercício utiliza  a função `useState` para criar um componente Contador que tem um valor numérico inicial de 0. Essa variável é atualizada de acordo com a ação do usuário - quando um dos botões "Incrementar" ou "Decrementar" é pressionado, o valor é atualizado com a ajuda da função setCount. Se o valor atual for 0, o botão "Decrementar" não tem efeito.**

&#x20;      **O botão "Resetar" também utiliza a função `setCount` para atualizar o valor para 0. Finalmente, é apresentada uma mensagem na tela caso o contador esteja zerado, usando uma condicional que verifica se a variável count é igual a 0.**

&#x20;**O uso de `useState` permite que o componente seja atualizado dinamicamente sem a necessidade de recarregar a página, tornando a experiência de um usuário no cenário real mais suave e responsiva.**
