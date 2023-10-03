# Virtual DOM.

## <mark style="color:blue;">O que é o DOM?</mark>

***

&#x20;           **`DOM` significa **_**Document**_ _**Object Model**_** (Modelo de Objeto de Documento). Ele é uma** [**API**](https://www.treinaweb.com.br/blog/o-que-e-uma-api/) **que nos permite acessar e manipular documentos** [**HTML**](https://www.treinaweb.com.br/blog/o-que-e-e-como-comecar-com-html-e-css/) **e** [**XML**](https://www.treinaweb.com.br/blog/o-que-e-xml/) **válidos. Esse modelo se estrutura em formato de árvore, com vários galhos que indicam diferentes elementos da página. Quando esse modelo é alterado através da linguagem de script, se altera a página da web — seja sua estrutura, estilo ou elementos.**

&#x20;          **Desse modo, o DOM possibilita a manipulação e modificação de elementos de um documento web ao conectar as linguagens de programação à página em questão.**

&#x20;          **Como toda página na web é um documento, os navegadores precisam fazer a leitura e a interpretação desses documentos para refletir seus conteúdos na tela do seu dispositivo num formato padrão. O DOM é a interface que representa a forma ou estrutura com que o documento será lido e exibido por todos os navegadores das redes.**

&#x20;          **O DOM define a estrutura lógica dos documentos em forma de árvore, a qual guia o navegador na representação e manipulação dos componentes da página. Assim sendo, abaixo indicamos como a “árvore DOM” é normalmente estruturada.**

### <mark style="color:blue;">Exemplo:</mark>

***

***

```html
<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>meu título</title>
</head>
  <body>
    <h1>meu cabeçalho</h1>
    <a>meu link</a>
  </body>
</html>
```

### <mark style="color:blue;">Este é  DOM</mark> <mark style="color:blue;"></mark>_<mark style="color:blue;">object tree</mark>_ <mark style="color:blue;"></mark><mark style="color:blue;">gerado:</mark>

***

<figure><img src="../.gitbook/assets/object tree.png" alt=""><figcaption><p>Object tree</p></figcaption></figure>

### <mark style="color:blue;">Como funciona o Virtual DOM no React?</mark>

***

**React cria uma árvore de objetos personalizados representando uma parte do DOM. Por exemplo, em vez de criar um elemento DIV real contendo um elemento UL, ele cria um objeto `React.div` que contém um objeto `React.ul`. Ele pode manipular esses objetos muito rapidamente sem realmente tocar no DOM real ou passar pela API do DOM. Então, quando ele renderiza um componente, ele usa esse DOM virtual para descobrir o que ele precisa fazer com o DOM real para que as duas árvores correspondam.**

<figure><img src="../.gitbook/assets/image (7).png" alt=""><figcaption><p>Virtual DOM e real DOM.</p></figcaption></figure>
