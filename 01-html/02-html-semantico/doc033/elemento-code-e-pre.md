# Como você representa código de computador em HTML?

O elemento de código inline é usado para representar pequenos trechos de código dentro do texto. Casos de uso comuns para o elemento de código seriam artigos técnicos e páginas de documentação.

Aqui está um exemplo de uso do **code** elemento para mostrar um trecho de código CSS:
```html
<p>
  To set the text color to blue in CSS, use the following code:
  <code>color: blue;</code>
</p>
```
Neste exemplo, a **color** propriedade CSS é usada para definir a cor do texto como blue. Ao envolver esse trecho de código dentro de **code** tags, ele comunica ao navegador que o texto é um trecho de código embutido.

O navegador aplicará estilos padrão ao conteúdo dentro do **code** elemento. O estilo padrão é uma fonte monoespaçada.

O **code** elemento deve representar uma única linha de código. Se quiser representar várias linhas de código, você precisará colocar um **code** elemento dentro de um elemento de texto pré-formatado.

O elemento de texto pré-formatado é usado para representar texto pré-formatado. Aqui está um exemplo de uso do elemento de texto pré-formatado para exibir uma declaração CSS:
```html
<pre>
  <code>
    body {
      color: red;
    }
  </code>
</pre>
```
Ao usar o **pre** elemento, você precisará estar atento ao espaçamento, pois ele será exibido exatamente como está escrito no documento HTML.

No navegador, você verá que o código está recuado vários espaços à direita. Se você alterar o recuo no exemplo de código, verá uma diferença no recuo na tela.

Quando se trata de incluir exemplos de código dentro do seu documento HTML, você deve usar o **code** elemento para exemplos inline curtos.

Se precisar exibir trechos de código mais longos, você precisará usar os elementos **pre** e **code**.

