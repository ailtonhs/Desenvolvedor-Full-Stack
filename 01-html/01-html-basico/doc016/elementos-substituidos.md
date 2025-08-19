# O que são elementos substituídos e quais são alguns exemplos?

Um elemento substituído é um elemento cujo conteúdo é determinado por um recurso externo e não pelo CSS. CSS, ou folhas de estilo em cascata, é usado para adicionar estilos a uma página web. Exemplos comuns de elementos substituídos incluem os elementos de imagem, iframe e vídeo.

Com elementos substituídos, você pode controlar a posição ou o layout de um elemento. Mas seu CSS não pode modificar diretamente o conteúdo desse elemento. Isso pode ser mais fácil de explicar com alguns exemplos. Considere o elemento image, que incorpora uma imagem na sua página web:

```html
<img src="example-img-url" alt="Descriptive text goes here">
```
O elemento em si é substituído pelo objeto externo: a imagem. Seu CSS pode controlar coisas como o posicionamento da imagem ou aplicar um filtro a ela, mas você não pode modificar a imagem em si. Um exemplo mais robusto pode ser o **iframe** elemento, que incorpora um site externo à sua página web:
```html
<iframe src="https://www.example.com" title="Example Site"></iframe>
```
Exemplos comuns de uso de **iframe** elemento seriam incorporar mapas ou vídeos do YouTube na página. O próprio elemento é substituído pelo objeto externo: o site. Seu CSS pode alterar o posicionamento do site incorporado, mas você não pode modificar o conteúdo do site. Para se aprofundar um pouco mais, se o site incorporar tiver um **h1** elemento, seu CSS não conseguirá estilizá-lo **h1**. Você não pode alterar o tamanho, a cor da fonte e assim por diante.

Existem outros elementos substituídos, como **video**, e **embed**. E alguns elementos se comportam como elemento substituídos em circunstâncias específicas. Aqui está um exemplo de um **input** elemento com o **type** atributo definido como **image**:
```html
<input type="image" alt="Descriptive text goes here" src="example-img-url">
```
Este tipo de **input** é considerado um elemento substituído, mas outros **input** tipo como **text**, ou **email** não são elementos substituídos.