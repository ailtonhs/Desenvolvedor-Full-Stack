# Quando você deve usar o elemento de ênfase em vez do elemento de texto idiomático?

Esses elementos estão intimamente relacionados aos conceitos de HTML de apresentação e semântico. O elemento de texto idiomático, **i**, era originalmente usado para fins de apresentação, exibindo o texto em itálico. Mas agora, é frequentemente usado para destacar vozes ou estados de espírito alternativos, termos idiomáticos de outro idioma, termos técnicos e pensamentos.

Aqui está um exemplo da especificação HTML oficial, usando o **i** elemento para mostrar uma frase idiomática em francês:
```html
<p>There is a certain <i lang="fr">je ne sais quoi</i> in the air.</p>
```

O **lang** atributo dentro da **&lt;i&gt;** tag open é usado para especificar o idioma do conteúdo. Neste caso, o idioma seria francês. O **i** elemento não indica se o texto é importante ou não, apenas mostra que ele é de alguma forma diferente do texto ao redor.

Se precisar enfatizar a importância do texto, você pode usar um elemento semântico semelhante, chamado elemento de ênfase. **em** Isso geralmente é recomendado se você precisar fornecer mais contexto. Você deve usar esse elemento para partes do texto que exigem uma ênfase especial em comparação com o texto ao redor. Geralmente, ele se limita a apenas algumas palavras, pois pode alterar o significado da frase.

Este é um exemplo do elemento de ênfase dentro de um parágrafo:

```html
<p>
  Never give up on <em>your</em> dreams.
</p>
```
Você pode ver a frase **Never give up on your dreams**. Observe que a palavra **your** estará enfatizada, pois está dentro deste elemento. No navegador, você verá a palavra **your** em itálico para informar aos leitores que se trata de uma palavra importante na frase.

Mesmo que pareça o mesmo quando o texto estava dentro do elemento de texto idiomático, o elemento de ênfase semântica transmite seu significado e importância nos bastidores.

É importante saber que esses elementos não devem ser usados ​​apenas para fins de apresentação. Se você precisar exibir o texto em itálico, mas ele não tiver um propósito, estilo ou significado específico no parágrafo, use CSS.

