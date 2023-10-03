# Exercício 1 - (Calculadora)

### <mark style="color:blue;">Descrição do exercício:</mark>

***

**Criar um exemplo de calculadora onde seja possível fazer as operações básicas.**

{% embed url="https://codesandbox.io/s/calculadora-s0ce3f?file=/src/styles.css" %}

### <mark style="color:blue;">Explicação:</mark>

**Este exemplo de calculadora utiliza um  `hook` do tipo `useState` para armazenar o resultado da calculadora e atualizá-lo conforme o usuário pressiona os botões.**

**A função `handleClick()` é responsável por atualizar o estado de resultado sempre que o usuário clica em um botão numérico ou operador. A função `handleClear()` é chamada quando o usuário clica no botão "C" e zera o resultado. Já a função `handleCalculate()` é chamada quando o usuário clica no botão de igual e usa a função `eval()` do JavaScript para calcular o resultado da expressão que foi digitada.**

**Dentro do retorno do componente, há uma div com a classe "calculator" que contém dois elementos filhos. O primeiro é uma div com a classe "screen" que mostra o resultado da calculadora. Se o resultado for vazio, ela mostra o valor "0". O segundo filho é uma div com a classe "buttons" que contém vários botões que representam os números, operadores e outras funções da calculadora.**

**Cada botão é definido com a propriedade "name" que é usada pela função `handleClick()` para atualizar o resultado. Além disso, alguns botões possuem uma classe CSS específica para serem estilizados como operadores (+, -, \* e /) ou para serem identificados como botões de limpeza (C) ou de resultado (=). Os eventos de clique são definidos por meio da propriedade `onClick` que chama a função correspondente.**
