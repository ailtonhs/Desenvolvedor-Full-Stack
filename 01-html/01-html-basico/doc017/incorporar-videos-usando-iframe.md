# Como você incorporar vídeos em sua página usando o elemento iframe?

Primeiro, o que exatamente é o **iframe**elemento? **iframe** significa "inline frame" . É um elemento inline usado para incorporar outro conteúdo HTML diretamente na página HTML. Esse conteúdo HTML pode ser um vídeo, um mapa, outro elemento HTML ou até mesmo outras páginas da web. Veja como é a sintaxe do **iframe** elemento:
```html
<iframe
  src="video-url"
  width="width-value"
  height="height-value"
  allowfullscreen
></iframe>
```
O **src** atributo especifica a URl da página que você deseja incorporar. O **width** atributo especifica a largura do **iframe**. O **height** atributo especifica a altura do **iframe**. O **allowfullscreen** atributo permite que o usuário exiba o **iframe** em tela cheia. Também é uma boa prática especificar um **title** atributo para o **iframe**, pois é importante para acessibilidade.

Para incorporar um vídeo, **iframe** você pode copiá-lo diretamente de serviços de vídeo populares como YouTube e Vimeo, ou defini-lo você mesmo com o **src** atributo apontando para a URL do vídeo. Veja um exemplo de incorporação de um curso popular do freeCodeCampo do YouTube:
```html
<h1>A freeCodeCamp YouTube Video Embedded with the iframe Element</h1>

<iframe
  width="560"
  height="315"
  src="https://www.youtube.com/embed/PkZNo7MFNFg?si=-UBVIUNM3csdeiWF"
  title="YouTube video player"
  allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
  referrerpolicy="strict-origin-when-cross-origin"
  allowfullscreen
></iframe>
```
Você pode então personalizá-lo **iframe** de acordo com suas necessidades ou até mesmo definir o seu próprio, copiando o link para o vídeo do YouTube e colando-o como valor de URL. A ressalva é que você deve substituir https://youtu.be por https://youtube.com/embed/.

youtu.be é o domínio quandoo você copia o link de compartilhamento e youtube.com/embed/ é o domínio necessário para incorporar vídeos com o **iframe** elemento. Aqui está um exemplo disso:
```html
<iframe
  src="https://youtube.com/embed/gp5H0Vw39yw?si=Rb_2nDK6abv1iIAM"
  title="freeCodeCamp Typescript Course"
  width="500"
  height="285"
  allowfullscreen
></iframe>
```
Observe que o vídeo pode vir de qualquer lugar. Não precisa vir de serviços de vídeo como YouTube e Vimeo. Aqui está um vídeo do Pixabay incorporado ao **iframe** elemento:
```html
<h1>A Video from Pixabay Embedded with the iframe Element</h1>

<iframe
  src="https://cdn.pixabay.com/video/2022/07/24/125310-733046613_large.mp4"
  width="500"
  height="285"
></iframe>
```
Não se esqueça de que você também pode incorporar um mapa, outra página da web ou HTML direto dentro do **iframe** elemento. Aqui está um mapa que consegui incorporar com o **iframe** elementoo:
```html
<h1>A Map from Openstreetmap.org Embedded with the iframe Element</h1>

<iframe
  width="425"
  height="350"
  src="https://www.openstreetmap.org/export/embed.html?bbox=3.006134033203125%2C6.150112578753815%2C3.6357879638671875%2C6.749850810550778&amp;layer=mapnik"
  style="border: 1px solid black"
>
</iframe>
<br />
<small>
  <a href="https://www.openstreetmap.org/#map=11/6.4501/3.3210">
    View Larger Map
  </a>
</small>
```

Se você quiser incorporar HTML direto dentro do **iframe** elemento, você terá que usar o **srcdoc** atributo em vez de **src**.