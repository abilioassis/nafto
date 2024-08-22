---
description: Dicas essenciais sobre tipografia, cores, espaçamento, layout e containers.
---

# Nafto UI Kit para React

## Introdução

O Nafto UI Kit para React é um arquivo do Figma disponibilizado pela Petrobras, usado por designers no desenvolvimento de aplicações React. Ele é baseado no Material UI for Figma.

<figure><img src="../../.gitbook/assets/image.png" alt=""><figcaption><p>O Nafto UI Kit para React é baseado no MUI for Figma</p></figcaption></figure>



## Tipografia

Os estilos de texto no Material UI utilizam a fonte **Roboto**, seguindo as definições tipográficas do **Material Design 2**. Esses estilos abrangem títulos (**h1..h6**), corpo de texto (**body1 e body2**), subtítulos (**subtitle1 e subtitle2**), linha superior (**overline**) e legenda (**caption**), além de estilos específicos para componentes como botões, DataPickers, menus e tabelas.

### Estilos de Texto e HTML Semântico <a href="#estilos-de-texto-e-html-semantico" id="estilos-de-texto-e-html-semantico"></a>

Os estilos de texto h1 a h6 no Material UI for Figma podem gerar confusão, pois no HTML5 esses termos têm significados específicos. No Figma, os designers usam esses títulos principalmente para criar uma hierarquia visual, não necessariamente seguindo a mesma hierarquia semântica do HTML.

No HTML, o h1 é para o título principal da página, seguido por h2 para subseções importantes, e assim por diante. Isso facilita a navegação e compreensão para pessoas com deficiência, conforme recomendações do Comitê de Acessibilidade do W3C. No Figma, o designer pode usar o estilo h1 para destacar visualmente uma seção importante, mas não necessariamente o título principal.

Por exemplo, ao projetar um site de notícias no Figma, o designer pode usar h1 para o nome do site no cabeçalho, h2 para títulos principais das notícias, h3 para subtítulos, e assim por diante. Visualmente, isso cria uma estrutura clara, mas no HTML, h1 deveria ser o título principal da página, como "Página Inicial" ou "Notícias".

Quando houver discrepância entre os estilos do Figma e a semântica HTML, o designer pode adicionar notas ao design. Por exemplo, se quiser que um texto tenha o estilo h3 no Figma, mas seja renderizado como `<h4>` no HTML, adicione uma nota explicando essa especificação. Isso garante que os desenvolvedores compreendam a intenção do design e apliquem os estilos corretamente.

### Mapeamento de Estilos de Texto para HTML5 <a href="#mapeamento-de-estilos-de-texto-para-html5" id="mapeamento-de-estilos-de-texto-para-html5"></a>

| Figma     | HTML   |
| --------- | ------ |
| h1        | `<h1>` |
| h2        | `<h2>` |
| h3        | `<h3>` |
| h4        | `<h4>` |
| h5        | `<h5>` |
| h6        | `<h6>` |
| subtitle1 | `<h6>` |
| subtitle2 | `<h6>` |
| body1     | `<p>`  |
| body2     | `<p>`  |





## Nafto UI Kit para React



## Estilos de Texto

Os estilos de texto no Material UI utilizam a fonte **Roboto**, seguindo as definições tipográficas do **Material Design 2**. Esses estilos abrangem títulos (**h1..h6**), corpo de texto (**body1 e body2**), subtítulos (**subtitle1 e subtitle2**), linha superior (**overline**) e legenda (**caption**), além de estilos específicos para componentes como botões, DataPickers, menus e tabelas.&#x20;

### Para Saber Mais <a href="#para-saber-mais" id="para-saber-mais"></a>

* [A escala tipográfica no Material Design 2](https://m2.material.io/design/typography/the-type-system.html#type-scale)
* [O componente Typography no Material UI](https://mui.com/material-ui/react-typography/)
