# O que são SVGs e quando você deve usá-los?

Primeiro, você precisa entender como as imagens funcionam. Formatos de imagem comuns, como PNG e JPG, são classificados como formatos raster. Isso significa essencialmente que são baseados em pixels, com os dados rastreando o valor da cor em cada pixel.

Uma grande desvantagem das imagens rasterizadas é que elas não podem ser ampliadas com facilidade. Se você já tentou aumentar o tamanho de um PNG, pode ter percebido que ele fica pixelado ou borrado.

Um SVG é um tipo diferente de imagem. SVG significa um gráfico vetorial escalável. Um gráfico vetorial rastreia dados com base em caminhos e equações para plotar pontos, linhas e curvas. O que isso significa é que um gráfico vetorial, assim como um SVG, pode ser redimensionado para qualquer tamanho sem afetar a qualidade.

Os SVGs têm o benefício adicional de armazenar dados em XML. Isso significa que você pode usá-los diretamente no seu código como HTML bruto com o **svg** elemento. Isso também significa que você pode alterar a cor da imagem programaticamente.

```html
<svg width="100" height="100" viewBox="0 0 100 100" xmlns="http://www.w3.org/2000/svg">
  <circle cx="50" cy="50" r="45" stroke="black" stroke-width="4" fill="yellow" />
  <circle cx="35" cy="40" r="5" fill="black" />
  <circle cx="65" cy="40" r="5" fill="black" />
  <path d="M35 65 Q50 80 65 65" stroke="black" stroke-width="4" fill="transparent" />
</svg>
```
Este código SVG desenha um rosto sorridente combinando alguns elementos básicos:

* O **svg** elemento é o contêiner de todo o desenho. Ele define o espaço onde todas as formas aparecem. Tudo o que você deseja desenhar com SVG, como círculos, linhas ou caminhos, fica dentro do svgelemento.
* O **circle** elemento é usado para fazer o rosto e os olhos. Um círculo grande forma o rosto amarelo e dois círculos menores formam os olhos.

* O **path** elemento é usado para desenhar o sorriso. Ele cria uma linha curva para a boca.

* Cada elemento SVG possui atributos que controlam sua aparência e posição na área de desenho.

* Então, quando você usaria um SVG? Um ótimo caso de uso é para ícones. Se você quiser criar marcadores personalizados ou adicionar ícones aos seus links para representar plataformas de mídia social, usar SVGs é a melhor abordagem. Uma das bibliotecas de ícones mais populares, a Font Awesome, usa imagens SVG para seus ícones. SVGs também são ótimos para logotipos de páginas da web, pois são perfeitamente dimensionados. Eles permitem que você adapte seu layout a qualquer design responsivo que precisar. Da próxima vez que você tiver um SVG localmente, tente abri-lo com um editor de texto e brincar com o código.

