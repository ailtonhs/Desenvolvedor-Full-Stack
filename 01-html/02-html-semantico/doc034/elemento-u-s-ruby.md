# Para que são usados ​​os elementos U, S e Ruby e como eles funcionam?

O elemento de anotação não articulado, ou uelemento para abreviar, é usado para representar texto embutido que tem anotação não textual aplicada.

Aqui está um exemplo de uso do **u** elemento para destacar vários erros de ortografia:
```html
<p>
  You can use the unarticulated annotation element to highlight
  <u>inccccort</u> <u>spling</u> <u>issses</u>.
</p>
```
No exemplo, as palavras **incorrect**, **spelling** e **issues** estão escritas incorretamente. O estilo padrão do uelemento é um sublinhado preto abaixo do texto.

Em HTML4, o **u** elemento era usado para fins de estilização. Já em HTML5, o **u** elemento deve ser usado apenas para indicar que o texto possui anotações não textuais aplicadas.

Se você quiser estilizar um pedaço de texto com um sublinhado, você deve usar CSS em vez de HTML.

O elemento tachado, ou **s** simplesmente elemento, deve ser usado para indicar quando o texto não é mais preciso ou relevante. Aqui está um exemplo de uso do selemento para indicar o cancelamento de uma atividade:
```html
<p><s>Tomorrow's hike will be meeting at noon.</s></p>

<p>Due to unforeseen weather conditions, the hike has been canceled.</p>
```
Neste exemplo, a primeira frase está riscada porque a caminhada foi cancelada devido a problemas climáticos.

O **s** elemento nunca deve ser usado apenas para mostrar alterações em um documento. Elementos mais apropriados nesse caso seriam o elemento de texto excluído e o elemento de texto inserido.

O **ruby** elemento representa um pequeno texto exibido acima ou abaixo do texto principal. Normalmente, é usado para indicar a pronúncia de caracteres do leste asiático. Aqui está o rubyexemplo do elemento da página de documentação do MDN:

O **rp** elemento, ou elemento parêntesis de fallback do Ruby, é usado como fallback para navegadores que não têm suporte para exibir anotações do Ruby.

O **rt** elemento, ou elemento de texto Ruby, é usado para indicar o texto da anotação Ruby. Este texto é geralmente usado para pronúncia ou detalhes de tradução na tipografia do Leste Asiático.

Embora o **ruby** elemento possa ser usado para outros tipos de anotações, o caso de uso mais comum é para tipografia do Leste Asiático.

