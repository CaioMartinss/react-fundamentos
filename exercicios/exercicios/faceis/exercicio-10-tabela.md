---
description: Criar uma lista de elemento(sendo id, nome e preço) e renderizar na tabela.
---

# Exercício - 10 (Tabela)

### <mark style="color:blue;">Descrição do exercício:</mark>

***

&#x20;C**riar uma tabela que recebe os dados de outro componente e renderiza-los.**

{% embed url="https://codesandbox.io/s/tabela-de-produtos-ko3tpf?file=/src/components/Tabela.jsx" %}
Exercício: Tabela
{% endembed %}

### <mark style="color:blue;">Explicação:</mark>

***

**Este código exporta um componente de tabela de produtos. Ele importa um arquivo CSS para estilizar a tabela e importa um array de produtos do arquivo de dados. Em seguida, usa o método `map` para criar uma lista de elementos de tabela a partir do array de produtos, adicionando o atributo `key` com o valor do `id` de cada produto para ajudar a React a identificar cada linha da tabela com exclusividade.**

**O componente retorna uma tabela HTML com cabeçalho e corpo, exibindo as informações de cada produto na tabela. O preço de cada produto é exibido com o prefixo "R$". As linhas da tabela são alternadamente estilizadas com classes CSS "par" e "impar" para facilitar a leitura dos dados. O componente é colocado em um contêiner com a classe CSS "tabelaprodutos" para permitir que o estilo seja aplicado apenas nesta tabela de produtos específica.**
