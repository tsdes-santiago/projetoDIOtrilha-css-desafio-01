<h1>
    <a href="https://www.dio.me/">
     <img align="center" width="40px" src="https://hermes.digitalinnovation.one/assets/diome/logo-minimized.png"></a>
    <span>Formação CSS Web Developer</span>
</h1>

# :computer: Desafio 01: Criando sua primeira Landing Page com HTML e CSS

Bem vindo(a) ao primeiro desafio da Trilha de CSS da DIO! Nela, você vai construir sua primeira Landing Page com HTML e CSS, colocando em prática os fundamentos do CSS,
as propriedades básicas da linguagem de estilização, além de trabalhar com as unidades de medidas relativas e absolutas que aprendemos ao longo da trilha.


Para você realizar o desafio, basta fazer um **fork** para o seu GitHub e começar a mexer no projeto.
Dentro da pasta *main*, você vai encontrar todas as imagens e o arquivo HTML, contendo a estrutura básica da sua página, faltando apenas
realizar a estilização da sua página. É necessário que você faça toda a parte responsável por interligar sua página HTML com suas folhas
de estilo para que o resultado da estilização funcione.

[Link do Figma](https://www.figma.com/file/3PiokoJj9IhGDnNiWAJbz7/DIO---Desafio-01?node-id=2%3A6) contendo o protótipo do desafio para
que você possa se basear.

*Observações: para aplicar os textos em gradiente, utilize a propriedade CSS background-clip, porém, para funcionar em alguns navegadores,
é necessário utilizar a propriedade -webkit-background-clip: text;*

O código-fonte base preparado para este Desafio de Projeto está versionado no GitHub, no seguinte endereço:

https://github.com/digitalinnovationone/trilha-css-desafio-01

# :bulb: Solução do desafio

Desafio feito com fork do repositório da instrutora. 
A propriedade -webkit-background-clip: text; foi adicionada no arquivo <b>assets/css/styles.css</b>

```CSS
  .banner h1 {
    font-size: 3rem;
    font-weight: 1000;
    text-transform: uppercase;
    color: transparent;
    background: -webkit-linear-gradient(#33A8DB, #1472B7);
    background-clip: text;
    -webkit-background-clip: text;
  }
```
Print screen da página:
<img src="pagina.png" alt='Print screen da página inteira.'/>

