# Qual é a função das tags Open Graph e como elas afetam o SEO?

O protocolo Open Graph permite que você controle como o conteúdo do seu site parece em diversas plataformas de mídia social, como Facebook, LinkedIn e muitas outras. Ao definir essas propriedades do Open Graph, você pode incentivar os usuários a clicarem e interagirem com o seu conteúdo. Você pode definir essas propriedades por meio de um conjunto de **meta** elementos dentro da sua **head** seção HTML.

A primeira propriedade importante do **OG** a ser incluída seria **title**. Aqui está um exemplo de configuração do OG **title** para a página inicial do freeCodeCamp:

```html
<meta content="freeCodeCamp.org" property="og:title"/>
```

Para o **property** atributo, você precisará especificar que ele é **og:title**. O **content** atributo é onde você escreverá o título que deseja exibir para sites de mídia social.

A próxima propriedade importante do OG seria o **type**. Aqui está um exemplo de uso do OG **type** para página inicial do freeCodeCamp:
```html
<meta property="og:type" content="website"/>
```
A **type** propriedade é usada para representar o tipo de conteúdo compartilhado nas redes. Exemplos desse conteúdo incluem artigos, sites, vídeos ou músicas.

A terceira propriedade importante do OG seria o **image**. Aqui está um exemplo de configuração do OG **image** para a página inicial do freCodeCamp:

```html
<meta
  content="https://cdn.freecodecamp.org/platform/universal/fcc_meta_1920X1080-indigo.png"
  property="og:image"
/>
```
Neste exemplo, a imagem do gráfico aberto aponta para o logotipo do freeCodeCamp. Todas essas imagens devem ser de alta qualidade, com boas dimensões e proporções. A maioria das plataformas de mídia social inclui critérios de requisitos de imagem para ajudar você a garantir que seu conteúdo seja exibido corretamente no site. Por exemplo, a página de documentação developers.facebook.com afirmaa:

"Use imagens com pelo menos 1200x630 pixels para melhor exibição em dispositivos de alta resolução. No mínimo, você deve usar imagens com 600x 315 pixels para exibir postagens de páginas de links com imagens maiores."

A quarta propriedade importante do OG seria o **url**. Aqui está um exemplo de configuração do OG **URL** para a página inicial do freeCodeCamp:
```html
<meta property="og:url" content="https://www.freecodecamp.org" />
```
Existem muitas outras propriedades OG que você pode definir, como **description**, **audio**, **video** e **locale**. No entanto, o gráfico aberto **url**, **image**, **type**, e **title** são os mais importantes a serem incluídos.

Então, comoo essas propriedades de gráfico aberto afetam a otimização para mecanismo de busca? Quando seu conteúdo é compartilhado nas redes sociais, propriedade de gráfico aberto bem elaboradas podem melhorar a aparência do seu conteúdo nos feeds dos usuários. Isso pode levar a taxas de cliques mais altas, o que pode indicar aos mecanismos de busca que seu conteúdo é relevante e envolvente.
