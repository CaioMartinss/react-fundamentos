# Exercício - 9 (Mensagem)

### <mark style="color:blue;">**Descrição do exercício:**</mark>

***

&#x20;**Este é um componente React com um campo de entrada controlado pelo estado `valor`. A função `quandoMudar` atualiza o estado `valor` quando o valor do campo é alterado. O estado `valor` é exibido em uma tag `h2` e em um campo de entrada somente leitura. O terceiro campo não tem valor definido. Para criar o componente, importe o React e `useState`. Na parte de retorno, exiba o valor do estado `valor` em uma tag `h2` e crie três campos de entrada, sendo que o primeiro tem seu valor definido como o estado `valor` e sua função `onChange` é definida como `quandoMudar`. O segundo campo é somente leitura e o terceiro não tem valor definido.**

{% embed url="https://codesandbox.io/s/mensagem-bmfder?file=/src/styles.css" %}
Exercício: Mensagem
{% endembed %}

### <mark style="color:blue;">Explicação:</mark>

***

**O código apresenta um componente React chamado "Form" que renderiza um formulário com uma caixa de seleção, uma área de texto e um botão de envio. O componente utiliza o hook "useState" para controlar o estado de duas variáveis, "to" e "mensagem", que representam o destinatário e o conteúdo da mensagem, respectivamente. O método "submit" é chamado quando o usuário envia o formulário, ele chama a função "setTimeout" para exibir uma mensagem de alerta após dois segundos informando o destinatário e a mensagem que foram enviadas. O valor selecionado no menu suspenso e na área de texto são atualizados quando o usuário interage com esses elementos usando as funções "setTo" e "setmensagem".**
