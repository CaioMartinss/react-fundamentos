---
description: >-
  Escreva uma função em React que recebe informações de um aluno (nome, nota) e
  retorna um parágrafo indicando se o aluno foi aprovado ou reprovado,
  juntamente com o status e uma cor correspondente.
---

# Exercício - 7 (Aprovado ou Não?)

### <mark style="color:blue;">**Descrição do exercício:**</mark>

&#x20;**Escreva uma função chamada `ComParametro(props)` que recebe um objeto `props` contendo o nome, nota e subtítulo do aluno. A função usa a nota para determinar se o aluno foi aprovado ou reprovado e cria um objeto de estilo para aplicar uma cor verde ou vermelha, respectivamente. A função retorna um parágrafo com o subtítulo, o nome do aluno, sua nota e seu status (aprovado/reprovado) dentro de uma `tag span` colorida.**

{% embed url="https://codesandbox.io/s/props-1w960z?file=/src/Props.jsx&from-embed=" %}

### <mark style="color:blue;">Explicação:</mark>

**Este é um componente funcional que recebe as propriedades `props` como parâmetro. O componente exibe o subtítulo, o nome e a nota do aluno, e a partir da nota, determina se o aluno está aprovado ou reprovado. Ele faz isso usando a expressão ternária que define o valor da variável `status` como "aprovado" ou "reprovado", dependendo do valor da propriedade `nota`. Em seguida, ele define um estilo condicional para a variável `estilo` com base no valor de `status`. Finalmente, o componente retorna um conjunto de parágrafos que exibem o subtítulo, o nome e a nota do aluno, juntamente com o status e o estilo condicional.**
