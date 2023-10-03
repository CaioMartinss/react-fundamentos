# Exercício 2 - (Lista de Filmes)

### <mark style="color:blue;">Descrição do exercício:</mark>

***

C**riar uma lista dentro de um card de filme onde é exibido a capa do filme, título e uma descrição.**

{% embed url="https://codesandbox.io/s/lista-de-filmes-bvxmgu?file=/src/App.js" %}

### <mark style="color:blue;">Explicação:</mark>

&#x20;     **Neste exemplo um array de objetos chamado "filmes" é criado. Cada objeto representa um filme e contém as propriedades "id", "titulo", "descricao" e "imagem". Essas informações são usadas posteriormente para renderizar a lista de filmes na tela.**

**Em seguida, a função "ListaFilmes" é definida. Essa função retorna um elemento React que contém um título e uma lista de filmes. A lista de filmes é gerada usando a função `map` do JavaScript, que itera sobre cada objeto no array "filmes" e retorna um elemento React para cada um deles.**

**Cada elemento na lista de filmes é representado por um "div" com a classe "filme". Dentro desse "div", há uma imagem com o caminho da imagem obtido a partir da propriedade "imagem" do objeto de filme, um título obtido da propriedade "titulo" e uma descrição obtida da propriedade "descricao". A propriedade "key" é definida para cada elemento na lista de filmes, garantindo que cada elemento tenha um identificador único.**
