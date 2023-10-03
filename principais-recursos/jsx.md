---
layout:
  title:
    visible: true
  description:
    visible: true
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
---

# JSX

## <mark style="color:blue;">O que é JSX ?</mark>

***

&#x20;**O JSX é uma mistura de HTML e javascript, com o JSX, podemos escrever os elementos HTML dentro do JavaScript e adicioná-los ao DOM sem utilizar métodos como `createElement()` ou `appendChild()`. o JSX é uma alternativa para escrevermos nosso código que mescla a estrutura do DOM com a lógica da aplicação. Entretanto, São necessários transpiladores (pré-processadores) como o Babel. Basicamente, com o JSX você escreve estruturas HTML/XML do mesmo modo que escreve o código JavaScript, então, o transpilador transformará essas expressões em código JavaScript. Ou seja, ao invés de colocar o JavaScript no HTML, colocamos o HTML no JavaScript.**

### <mark style="color:blue;">Exemplo:</mark>

***

```jsx
function ListaDeFrutas() {
  return (
    <ul>
      <li>Maçã</li>
      <li>Pera</li>
      <li>Banana</li>
    </ul>
  );
}

```

### <mark style="color:blue;">Transpilado pelo</mark> [<mark style="color:blue;">babel</mark>](https://babeljs.io/)<mark style="color:blue;">:</mark>

***

```javascript
function ListaDeFrutas() {
  return /*#__PURE__*/ React.createElement("ul", null, 
  /*#__PURE__*/ React.createElement("li", null, "Ma\xE7\xE3"), 
  /*#__PURE__*/ React.createElement("li", null, "Pera"), 
  /*#__PURE__*/ React.createElement("li", null, "Banana"));
}
,

```

### <mark style="color:blue;">Ilustração de Transpilação:</mark>

***

<figure><img src="../.gitbook/assets/baebel certo.png" alt=""><figcaption><p>Transpilação com o babel</p></figcaption></figure>
