# Como funcionam aspas em bloco e em linha em HTML?

Em HTML, elementos entre aspas são usados ​​para distinguir o texto citado do conteúdo ao redor. Isso confere ao texto citado um formato fácil de identificar.

Você deve usar o elemento "citação em bloco" para representar uma seção citada de outra fonte. Ele é usado principalmente para citações extensas. Se a fonte da citação tiver um endereço, você pode citá-la com o **cite** atributo . O valor deste atributo deve ser uma URL válida. Este é um exemplo de uma citação dentro de um elemento "citação em bloco":
```html
<blockquote cite="https://www.freecodecamp.org/news/learn-to-code-book/">
  "Can you imagine what it would be like to be a successful developer? To have built software systems that people rely upon?"
</blockquote>
```

Este elemento possui um **cite** atributo. O valor do **cite** atributo é a URL da fonte. Embora este atributo não altere a apresentação da citação em bloco, é muito útil para fornecer aos leitores de tela e mecanismos de busca mais informações sobre a citação. No navegador, você verá que o texto está ligeiramente recuado.

Se você quiser iniciar e terminar a citação em bloco com aspas, talvez seja necessário escrevê-las explicitamente no texto. Você pode escrever o texto diretamente dentro do elemento de citação em bloco, como eu acabei de fazer, ou envolvê-lo em um ou mais elementos de parágrafo. Isso é útil quando o texto tem vários parágrafos, mas você quer mantê-los dentro da mesma citação em bloco. Aqui está um exemplo com quatro parágrafos:
```html
<blockquote cite="https://www.freecodecamp.org/news/learn-to-code-book/">
  <p>Build your projects. Show them to your friends. Build projects for your friends.</p>
  <p>Build your network. Help the people you meet along the way. What goes around comes around. You'll get what's coming to you.</p>   
  <p>It is not too late. Life is long.</p>
  <p>You will look back on this moment years from now and be glad you made a move.</p>
</blockquote>
```
Todos os parágrafos estão contidos no mesmo elemento de citação em bloco, portanto, fazem parte da mesma citação. Você pode ver que o elemento possui um **cite** atributo com a URL da fonte. No navegador, você verá que os quatro parágrafos estão alinhados entre si, mas recuados em relação ao seu contêiner.

Até agora, tenho usado o **cite** atributo para atribuir a fonte da citação, mas o atributo não mostra a fonte ao usuário. Funciona apenas nos bastidores.

Se quiser atribuir a fonte visualmente, você pode adicionar um elemento de citação, **cite**, fora do elemento de citação em bloco. Isso é diferente do **cite** atributo. O elemento de citação é um elemento HTML que você pode usar para marcar o título de uma obra criativa referenciada, como um artigo de livro, música, filme, site ou artigo de pesquisa. Veja um exemplo:
```html
<div>
  <blockquote cite="https://www.freecodecamp.org/news/learn-to-code-book/">
    Can you imagine what it would be like to be a successful developer? To have built software systems that people rely upon?
  </blockquote>
  <p>—Quincy Larson, <cite>How to Learn to Code and Get a Developer Job [Full Book].</cite></p>
</div>
```
O elemento de citação em bloco contém o texto citado. Abaixo do elemento, você pode ver um elemento de parágrafo com o nome do autor, seguido por um elemento de citação. O elemento de citação contém o título do livro de onde a citação foi retirada.

Se você acessar o navegador, a fonte ficará claramente visível e você verá que a citação vem de um livro escrito por Quincy Larson. O título deste livro é **How to Learn to Code and Get a Developer Job**.

Você deve usar citações em bloco como estas para citações longas de outras fontes. Mas, às vezes, você só precisará citar algumas palavras dentro de um parágrafo maior.

É exatamente para isso que serve o elemento de citação em linha. Ele serve para citações curtas em linha de outras fontes. A maioria dos navegadores modernos adiciona aspas ao redor da citação em linha automaticamente quando você usa este elemento. Este é um exemplo:
<p>
  As Quincy Larson said,
  <q cite="https://www.freecodecamp.org/news/learn-to-code-book/">
    Momentum is everything.
  </q>
</p>
```
Você pode ver um elemento de parágrafo que contém texto. Parte do texto é uma citação embutida, pois está dentro do elemento de citação embutida. Você também pode adicionar um **cite** atributo para atribuir a fonte.

Isso funciona exatamente da mesma forma que com o elemento de citação em bloco. Não haverá nenhuma alteração visual, mas fornecerá aos leitores de tela e aos mecanismos de busca mais informações sobre a citação.

No navegador, você verá que o texto citado faz parte do parágrafo e está entre aspas. A maioria dos navegadores modernos adiciona essas aspas automaticamente.

Qual é a diferença entre citações em bloco e citações em linha? Você deve usar citações em bloco para citações estendidas de outras fontes e citações em linha para citações curtas de outras fontes que devem fazer parte de parágrafos existentes.

