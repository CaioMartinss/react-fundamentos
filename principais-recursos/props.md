# Props

## <mark style="color:blue;">Props</mark>

***

&#x20;      **Props, que é uma abreviação de **_**properties**_**, ou propriedades, são informações que podem ser passadas para um componente. Pode ser uma **_**string**_**, um número, até mesmo uma função. Este valor pode então ser utilizado pelo componente que a recebe.**

### <mark style="color:blue;">Exemplo:</mark>

***

{% embed url="https://codesandbox.io/embed/affectionate-benji-1w960z?fontsize=14&hidenavigation=1&theme=dark" %}

### <mark style="color:blue;">Explicação:</mark>

***

**O código cria um componente React chamado `ComParametro` que recebe as propriedades `nome`, `nota` e `subtítulo` como parâmetros.**

**O primeiro bloco de código usa uma expressão ternária para verificar se a nota é maior ou igual a 7. Se for, a constante `status` recebe o valor "aprovado", senão recebe "reprovado".**

**Em seguida, a constante `estilo` é definida como um objeto que contém a propriedade `backgroundColor`. O valor dessa propriedade é definido com base na variável `status`. Se `status` for "aprovado", o valor de `backgroundColor` será "green", senão será "red".**

**Por fim, o componente retorna uma estrutura HTML que exibe as informações passadas como parâmetro e usa o estilo definido acima para exibir a cor de fundo do elemento `<span>` que exibe o status.**
