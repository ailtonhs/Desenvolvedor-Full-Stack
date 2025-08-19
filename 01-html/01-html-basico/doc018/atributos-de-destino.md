# Quais são os diferentes tipos de atributos de destino e como eles funcionam?

Você pode ter visto o **target** atributo em elementos âncora ou links. Este atributo importante informa ao navegador onde abrir a URL do elemento âncora:

```html
<a href="https://freecodecamp.org" target="_blank">Visit freeCodeCamp</a>
```
Há quatro valores possíveis importantes para este atributo. Observe que cada valor é precedido por um sublinhado.

O primeiro valor é **_self**, que é o valor padrão. Isso abre o link no contexto de navegação atual. Na maioria dos casos, esta será a aba ou janela atual.

O segundo valor é **_blank**, que abre o link em um novo contexto de navegação. Normalmete, isso abre em uma nova aba. Mas alguns usuários podem configurar seus navegadores para abrir uma nova janela.

O terceiro valor é **_parent**, que abre o link no contexto pai do contexto atual. Por exemplo, se o seu site tiver um **iframe**, um **_parent** valor em **iframe** abriria na aba/janela do seu site, não no quadro incorporado.

O quarto valor é **_top**, que abre o link no contexto de navegação mais alto - pense em "o pai do pai". É semelhante a **_parent**, mas o link sempre abrirá na aba/janela completa do navegador, mesmo para frames incorporados aninhados.

Há um quinto valor, chamado **_unfencedTop**, que é usado atualmente na API experimental FencedFrame. No momento desta aula, você provavelmente ainda não terá um motivo para usá-lo.

Selecionar o valor certo **target** para controlar onde seus usuários chegam é uma consideração importante ao criar um site.