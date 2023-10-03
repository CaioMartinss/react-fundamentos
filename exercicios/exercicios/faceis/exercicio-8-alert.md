---
description: Escrever uma função que exiba um alert por meio de um botão
---

# Exercício - 8 (Alert)

### <mark style="color:blue;">**Descrição do exercício**</mark><mark style="color:blue;">:</mark>&#x20;

***

**criar uma função chamada `BotaoAcao`  passando dois parâmetros e retornar o valor desses parâmetros por meio da função `onClick`  sendo exibida no `alert`.**

{% embed url="https://codesandbox.io/s/mostrando-mensagem-fkx7r0?file=/src/styles.css" %}
Exercício: Alert.
{% endembed %}

### <mark style="color:blue;">Explicação:</mark>

***

**O código apresenta uma função chamada `BotaoAcao` que recebe dois parâmetros desestruturados: `msg` e `children`. A função retorna um botão com a mensagem `children` e uma função de clique que exibe um alerta com a mensagem `msg`. O `children` é utilizado para renderizar qualquer conteúdo entre as tags de abertura e fechamento do componente `BotaoAcao`. O componente é exportado por padrão para ser utilizado em outros arquivos do projeto.**
