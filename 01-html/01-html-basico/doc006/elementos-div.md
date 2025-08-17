# O que são elementos Div e quando você deve usá-los?

Agora que entendemos o que é HTML, vamos à parte divertida! Voou dar uma olhada no elemento de Divisão de Conteúdo - ou, em outras palavras, o **div**:
```html
<div></div>
```
Gosto de pensar no **div** como um ser belo que pode ser o que você quiser. Podemos dar a ele um **div**, **height** podemos dar a ele um **width**, e podemos dar a ele uma cor de fundo usando CSS - ou, em outras palavras, estilo, que abordaremos em próximas aulas.

Também podemos usá-lo de forma bem básica, sem estilização, para manter outros elementos unidos. Por exemplo, podemos criar um **div** e inserir um título nele, e um parágrafo nele, e agora esses dois elementos serão agrupados:
```html
<div>
    <h1>I am a heading</h1>
    <p>I am a paragraph</p>
</div>
```

Esteja ciente de que pode haver elementos melhores para usar ao agrupá-los. Você pode escolher um **section** elemento, por exemplo.
```html
<section>
    <h1>I am a heading</h1>
    <p>I am a paragraph</p>
</section>
```

Isso ocorre porque o **section** elemento tem significado semântico. Semântica é o significado de palavras ou frases em uma linguagem. Em HTML, que é uma linguagem, os elementos também têm seu próprio significado semântico. Isso significa que, se você usar um **section** elemento, o navegador captará seu significado semântico e o entenderá como uma seção - em desktops, celulares, etc.

Aprofundaremos esse assunto mais adiante. Por enquanto, saiba apenas que o **div**, não tem isso. É como um fantasma misterioso. Vamos ver o que mais podemos fazer com um **div**, nas próxima aula.