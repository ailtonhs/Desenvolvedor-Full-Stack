# O que são entidades HTML e quais são alguns exemplos comuns?

Uma entidade HTML, ou referência de caractere, é um conjunto de caracteres usado para representar um caractere reservado em HTML. Neste exemplo, há um elemento de parágrafo com um elemento de imagem aninhado dentro:

```html
<p>This is an <img/> element</p>
```
O texto na tela deveria dizer **This is an &lt;img/&gt; element**. No entanto, o texto atual diz: **this is an element**. Isso acontece porque, quando o analisador HTML vê o simbolo de menor que **(<)** seguido por um nome de tag HTML, ele o interpreta como um elemento HTML.

**>**Para corrigir esse problema, você pode usar entidades HTML. AQui está um exempo atualizado usando as entidades HTML corretas para os símbolos **menor que** e **maior que**.

```html
<p>This is an &lt;img/&gt; element</p>
```
Esses tipos de referências nomeadas começam com um sinal de "e" comercial **(&)** e termina com um ponto e vírgula **(;)**. Ao usar uma refeência de caractere nomeado, o analizador de HTML não a confundirá com um elemento HTML real. Veja como o elemento de parágrafo atualizado se parece na página: **This is an &lt;img/&gt; element**. Agora, os usuários poderão ver toda a sintaxe do elemento de imagem comforme vocẽ pretendia.

Outro tipo de referência de caractere seria a referência numérica decimal. Aqui está um exemplo de uso da referência numérica decimal para o símbolo de menor que:
```html
&#60;
```
Esta referência de caractere começa com um sinal de "e" comercial e um símbolo de hash (**#**), seguidos por um ou mais dígitos decimais, seguidos por um ponto e vírgula.

O último tipo de referência de caractere seria a referência numérica hexadecimal. Aqui está um exemplo de uso da referência numérica hexadecimal para o símbolo de menor que:
```html
&#x3C;
```

Esta referência de caractere começa comum sinal de ""e** comercial, um símbolo de cerquilha **x**. Em seguida, é seguida por um ou mais dígitos hexadecimais ASCII e termina com um ponto e vírgula.

Então, quais são outros exemplos de uso de entidades HTML? Bem, você frequentemente as vê usadas para símbolos como o símbolo de direitos autorais ( ©), aspas ( "), símbolo de marca registrada ( ™) e o sinal de "e" comercial.
