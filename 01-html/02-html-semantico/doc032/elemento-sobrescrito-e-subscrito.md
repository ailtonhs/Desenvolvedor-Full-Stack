# Como exibir equações matemática e fórmulas químicas em HTML?

O elemento sobrescrito é usado para exibir um trecho de texto como sobrescrito. Um sobrescrito é um símbolo ou letra imprsso acima da linha normal do texto.

Aqui está um exemplo usando o elemento sobrescrito para ilustrar expoentes:
```html
<p>2<sup>2</sup> (2 squared) is 4.</p>
```
Neste exemplo, o número 2 está encapsulado em **sup** tags para representar o sobrescrito dentro do parágrafo. No navegador, você verá que o segundo número 2 é menor e ligeiramente maior que o primeiro.

Casos de uso comuns para o elemento sobrescrito incluem expoentes, letras superiores e números ordinais. Aqui está um exemplo usando o elemento sobrescrito para letras superiores:
```html
<p>
  Monseigneur is often written as <strong>M<sup>gr</sup></strong>.
</p>
```
Letras superiores referem-se a letras escrita em sobrescrito, geralmente para indicar abreviações. As letras **g** e **r** estão dentro de tags de sobrescrito para ilustrar a abreviação neste exemplo.

É importante observar que o elemento sobrescrito deve ser usado apenas por motivos tipográficos. Se você quiser estilizar um trecho de texto com uma linha de base elevada, use CSS em vez do elemento sobrescrito.

Para representar equações químicas em HTML, você usaria o elemento subscrito. Este elemento usa um subscrito que exibe uma linha de base rebaixada com texto menor.


Aqui está um exemplo de uso do elemento subscrito para mostrar a representação química do dióxido de carbono.
```html
<p>CO<sub>2</sub></p>
```
O número dois é encapsulado dentro de **sub** tags para ilustrar que o caractere deve ser um subscrito.

Casos de uso comuns para o elemento subscrito incluem fórmulas químicas, notas de rodapé e subscritos variáveis.