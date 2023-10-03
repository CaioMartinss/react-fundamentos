---
description: Cria um componente que mude de estado.
---

# Exercício - 6 (Estado)

### <mark style="color:blue;">**Descrição do exercício:**</mark>

&#x20;**Este é um componente React com um campo de entrada controlado pelo estado `valor`. A função `quandoMudar` atualiza o estado `valor` quando o valor do campo é alterado. O estado `valor` é exibido em uma `tag h2` e em um campo de entrada somente leitura. O terceiro campo não tem valor definido. Para criar o componente, importe o React e `useState`. Na parte de retorno, exiba o valor do estado `valor` em uma tag `h2` e crie três campos de entrada, sendo que o primeiro tem seu valor definido como o estado `valor` e sua função `onChange` é definida como `quandoMudar`. O segundo campo é somente leitura e o terceiro não tem valor definido.**

{% embed url="https://codesandbox.io/s/state-estadp-ftmjgr?from-embed=" %}

### <mark style="color:blue;">Explicação:</mark>

**Este é um componente React que define um botão clicável que atualiza uma contagem de cliques quando o usuário clica nele. O componente utiliza o hook useState para armazenar o valor atual da contagem de cliques em uma variável de estado chamada "count". O valor inicial da contagem é 0.**

**O componente exibe o valor atual da contagem em um elemento "p" e exibe um botão que, quando clicado, chama a função handleClick para atualizar a contagem. A função handleClick é definida usando uma arrow function e utiliza o método setCount para atualizar o valor da contagem adicionando 1.**

**Então, toda vez que o botão é clicado, o valor da contagem é atualizado e a mensagem é renderizada novamente com o novo valor da contagem.**
