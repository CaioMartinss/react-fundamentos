---
description: Criar uma função para exibir se um numero é impar ou par.
coverY: 0
layout: landing
---

# Exercicio - 2 (ímpar ou par)

### <mark style="color:blue;">**Descrição do exercício:**</mark>

&#x20;**Este é um componente React que recebe uma propriedade chamada `numero`. Ele verifica se o número é par ou ímpar por meio da expressão `props.numero % 2 === 0` e armazena o resultado em uma constante chamada `isPar`. Em seguida, o componente renderiza um elemento `div` que contém um elemento `span` contendo a palavra "Par" se o valor de `isPar` for verdadeiro ou "Impar" caso contrário. Ou seja, o componente exibe "Par" se `numero` for um número par e "Impar" se for um número ímpar.**

{% embed url="https://codesandbox.io/s/hopeful-meadow-hvpxmh?file=/src/styles.css" %}
Exercício: Ímpar ou par.
{% endembed %}

### <mark style="color:blue;">Explicação:</mark>

**O código define um componente React  que recebe uma propriedade chamada `numero` como parâmetro.**

**O primeiro bloco de código define a constante `isPar` que verifica se o número passado como parâmetro é par ou ímpar. Para isso, o código usa o operador `%` para verificar se o resto da divisão por 2 é igual a zero.**

**Por fim, o componente retorna uma estrutura HTML que exibe "Par" ou "Impar" com base no resultado da verificação da constante `isPar`, usando uma expressão ternária para selecionar qual dos dois textos exibir.**

**Em resumo, o código define um componente React que recebe um número como parâmetro e exibe se o número é par ou ímpar na tela. O componente usa uma expressão ternária para selecionar qual texto exibir com base no resultado da verificação da constante `isPar`.**
