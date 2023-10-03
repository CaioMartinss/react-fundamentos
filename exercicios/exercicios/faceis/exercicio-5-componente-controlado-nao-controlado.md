---
description: Criar dois componentes um controlado e outro não.
---

# Exercício - 5 (Componente controlado/ não controlado)

### <mark style="color:blue;">**Descrição do exercício**</mark><mark style="color:blue;">:</mark>

&#x20;C**riar um componente controlado e o outro não(manuseável).**

{% embed url="https://codesandbox.io/s/componentes-controlados-nao-controlados-zkvfy4?file=/src/components/Input.jsx" %}

### <mark style="color:blue;">Explicação:</mark>

**Este código é um componente React que renderiza um formulário com três campos de entrada (input). O valor dos dois primeiros campos é vinculado à variável "valor" por meio do useState Hook, enquanto o terceiro campo não tem nenhum valor atribuído. Quando o usuário digita algo no primeiro campo, a função "quandoMudar" é chamada e atualiza o estado do componente com o novo valor do campo. O segundo campo é somente leitura, o que significa que o usuário não pode editar seu conteúdo. O terceiro campo não tem valor atribuído e, portanto, aparece em branco.**
