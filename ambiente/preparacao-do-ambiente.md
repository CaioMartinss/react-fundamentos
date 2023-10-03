# Preparação do Ambiente

## [NodeJs](https://nodejs.org/en)

**Node: Node.js é uma plataforma de software de código aberto construída em cima do motor de JavaScript V8 do Google Chrome. Ela permite que os desenvolvedores criem aplicativos do lado do servidor usando JavaScript**

## [Visual Studio Code(IDE)](https://code.visualstudio.com/)

**O visual Studio Code é uma plataforma de desenvolvimento de código que suporta diversas linguagens, e uma das suas vantagens é a imensa variedade de extensões que tornam a programão mais pratica.**

## [Github](https://github.com/)(Opcional)

**GitHub é uma plataforma de hospedagem de código-fonte e arquivos com controle de versão usando o Git. É como uma plataforma social colaborativa, onde programadores e empresas colocam seus projetos para o desenvolvimento do código**

{% hint style="info" %}
Não utilizar o ~~`create-react-app`~~

**Sugestão:**  Utilizar o [Vite ](https://vitejs.dev/)para criar as aplicações do React.
{% endhint %}

**O CRA é uma ferramenta de linha de comando que ajuda a criar um novo projeto React com uma configuração padrão. Ele vem com todas as dependências necessárias e um ambiente de desenvolvimento configurado prontos para serem utilizados. Por outro lado, o Vite é um construtor de projetos que se concentra na eficiência de desenvolvimento em ambientes de desenvolvimento modernos. Ele é projetado para ser mais rápido e mais leve do que o CRA.**

**Mas por que o Vite está se tornando a nova escolha padrão para projetos React? Vamos dar uma olhada em algumas das principais diferenças entre essas duas ferramentas.**

* **Mais rápido e mais leve do que o Create-React-App**
* **Usa o esbuild para compilação, que é significativamente mais rápido do que o webpack**
* **Permite que os desenvolvedores construam e recarreguem projetos mais rapidamente**
* **Projetado para trabalhar com outras tecnologias modernas, como o TypeScript e o Vue.js (Vite e Vue.js têm o mesmo criador, Evan You)**
* **Possui um ambiente de desenvolvimento mais moderno e atualizado**
* **Suporta HMR (Hot Module Replacement) para atualizações de módulo mais rápidas durante o desenvolvimento**
* **Permite importações dinâmicas com melhor suporte a tipos para otimização de carregamento de módulos**
* **Oferece uma experiência de desenvolvimento mais suave e produtiva em geral.**

**Outra diferença importante é a forma como eles lidam com a inicialização do projeto. O CRA cria uma configuração padrão para o projeto, o que significa que você tem menos controle sobre a estrutura do projeto, tendo que ejetá-lo para fazer qualquer configuração personalizada. O Vite permite que você escolha como deseja configurar seu projeto, dando aos desenvolvedores mais flexibilidade e controle.**

## Comandos:

<pre class="language-bash" data-overflow="wrap" data-line-numbers data-full-width="false"><code class="lang-bash"><strong>//Instalar o vite
</strong>npm install -g vite

<strong>//Criar a aplicação com Vite:
</strong> npm create vite@latest
 
<strong>//abrir a pasta
</strong> cd nomedoseuprojeto
 
//instalar as dependências
 npm install
 
//rodar a aplicação
 npm run dev
 
 //comando rápido
 npm init @vitejs/app nomedoprojeto --template react
</code></pre>

## IDE online:

### [Code sand box](https://codesandbox.io/dashboard/recent?workspace=5a82fa25-8abe-4d70-a7ac-bffad8805329)
