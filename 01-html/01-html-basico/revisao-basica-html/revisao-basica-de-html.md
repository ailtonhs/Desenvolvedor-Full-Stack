# Revisão básica de HTML

## Noções básicas de HTML
 * **Função do HTML**: O HTML representa o conteúdo e a estrutura da página web.

 * **Elementos HTML**: Os elementos são os blocos de construção de um documento HTML. Eles representam títulos, parágrafos, links, imagens e muito mais. A maioria dos elementos HTML consiste em uma tag de abertura (**&lt;elementName&gt;)** e uma tag de fechamento (**&lt;/elementname&gt;**).

 Aqui está a sintaxxe básica:
 ```
 <elementName>Content goes here</elementName>
```

* **Elementos Vazios**: Elementos vazios não podem ter conteúdo e possuem apenas uma tag inicial. Exemplos incluem elementos **img** e **meta**.
```html
<meta>
<img>
```
É comum ver algumas base de código que incluem uma barra **/** dentro do elemento void. Ambos são aceitáveis:
``html
<img>
<img/>
```

* **Atributos**: Um atributo é um valor inserido na tag de abertura de um elemento HTML. Os atributos fornecem informações adicionais sobre o elemento ou especificam como ele deve se comportar. Aqui está a sintaxe básica de um atributo:
```
<element attribute="value"></element>
```
Um atributo booleano é um atributo que pode estar presente ou ausente em uma tag HTML. Se presente, o valor é true, caso contrário, é false. Exemplos de atributos booleanos incluem **disabled**, **readonly** e **required**.

* **Comentários**: Comentários : Comentários são usados em programação para deixar anotações para você e outros desenvolvedores no seu código. Aqui está a sintaxe para um comentário em HTML:
```html
<!--This is an HTML comment.-->
```

## Elementos HTML comuns

* **Elementos de Título**: Existem seis elementos de título em HTML. Os elementos de título **h1** intermediários **h6** são usados para indicar a importância do conteúdo abaixo deles. Quanto menor o número, maior a importância, portanto, **h2** os elementos têm menos importância do que **h1** os elementos.
```html
<h1>most important heading element</h1>
<h2>second most important heading element</h2>
<h3>third most important heading element</h3>
<h4>fourth most important heading element</h4>
<h5>fifth most important heading element</h5>
<h6>least important heading element</h6>
```
* **Elementos de parágrafo**: usado para parágrafos em uma página da web.
```html
<p>This is a paragraph element.</p>
```
* **Elementos img**: O **img** elemento é usado para adicionar imagens à página web. O **src** atributo é usado para especificar o local dessa imagem. Para elementos de imagem, é uma boa prática incluir outro atributo chamado **alt** atributo. Veja um exemplo de um **img** elemento com os atributos **src** e **alt**:
```html
<img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/lasagna.jpg" alt="A slice of lasagna on a plate.">
```
* **Elemento body**: Este elemento é usado para representar o conteúdo do documento HTML.
```html
<body>
  <h1>CatPhotoApp</h1>
  <p>This is a paragraph element.</p>
</body>  
```
* **Elemento section**:  Este elemento é usado para dividir o conteúdo em seções menores.
```html
<section>
  <h2>About Me</h2>
  <p>Hi, I am Jane Doe and I am a web developer.</p>
</section>
```
* **Elemento div**:  Este elemento é um elemento HTML genérico que não possui nenhum significado semântico. Ele é usado como um contêiner genérico para armazenar outros elementos HTML.
```html
<div>
  <h1>I am a heading</h1>
  <p>I am a paragraph</p>
</div>
```
* **Elemento âncora(a)**: Esses elementos são usados para aplicar links a uma página da web. O **href** atributo é usado para especificar para onde o link deve ir quando o usuário clicar nele.
```html
<a href="https://cdn.freecodecamp.org/curriculum/cat-photo-app/running-cats.jpg">cute cats</a>
```
* **Elementos de lista não ordenados (ul) e ordenados (ol)**:  para criar uma lista com marcadores de itens, você deve usar o **ul** elemento com um ou mais **li** elementos aninhados dentro, como este:
```html
<ul>
  <li>catnip</li>
  <li>laser pointers</li>
  <li>lasagna</li>
</ul>
```
Para criar uma lista ordenada de itens, vocẽ deve usar o **ol** elemento:
```html
<ol>
  <li>flea treatment</li>
  <li>thunder</li>
  <li>other cats</li>
</ol>
```

* **Elemento de ênfase (em)**: usado para dar ênfase a um trecho de texto.
```html
<p>Cats <em>love</em> lasagna.</p>  
```
* **Elemento de forte importância(strong)**: Este elemento é usado para dar forte ênfase ao texto e indicar um senso de urgência e seriedade.
```html
<p>
  <strong>Important:</strong> Before proceeding, make sure to wear your safety goggles. 
</p>
```
* **Elementos figure e figcaption**: O **figure** elemento é usado para agrupar conteúdo como imagens e diagramas. O **figcaption** elemento é usado para representar uma legenda para esse conteúdo dentro do **figure** elemento.
```html
<figure>
  <img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/cats.jpg" alt="Two tabby kittens sleeping together on a couch.">
  <figcaption>Cats <strong>hate</strong> other cats.</figcaption>  
</figure>
```

* **Elemento main**: Este elemento é usado para representar o conteúdo principal de uma página da web.

* **Elemento footer**: Este elemento é colocado na parte inferior do documento HTML e geralmente contém informações de direitos autorais e outros links de páginas importantes.
```html
<footer>
  <p>
    No Copyright - <a href="https://www.freecodecamp.org">freeCodeCamp.org</a>
  </p>
</footer>
```

## Identificadores e Agrupamento**

* **IDs**: Identificadores de elementos exclusivos para elementos HTML. Os nomes de ID devem ser usados apenas uma vez por documento HTML.
```html
<h1 id="title">Movie Review Page</h1>
```
Nomes de ID não podem ter espaços. Se o seu nome de ID contiver várias palavras, você pode usar hífens entre elas, como este:


* **Classes**: As classes são usadas para agrupar elementos para estilo e comportamento.
```html
<div class="box"></div>
```
Ao contrário dos IDs, você pode reutilizar o mesmo nome de classe em todo o documento HTML. O **class** valor também pode ter espaços como este:
```html
<div class="box red-box"></div>
<div class="box blue-box"></div>
```

## Caracteres especiais e vinculação

* **Entidades HTML**: Uma entidade HTML, ou referência de caractere, é um conjunto de caracteres usado para representar um caractere reservado em HTML. Exemplos incluem o símbolo "&" comercial `&amp;`  e o símbolo de "`<`" menor que `&lt;`.
```html
<p>This is an &lt;img /&gt; element</p>
```
* **Elemento link**: Este elemento é usado para vincular recursos externos, como folhas de estilo e ícones de sites. Esta é a sintaxe básica para usar o **link** elemento em um arquivo CSS externo:
```html
<link rel="stylesheet" href="./styles.css" />
```
O **rel** atributo é usado para especificar a relação entre o recurso vinculado e o documento HTML. O **href** atributo é usado para especificar a localização da URL do recurso externo.

* **elemento script**: Este elemento é usado para incorporar código executável.
```html
<body>
  <script>
    alert("Welcome to freeCodeCamp");
  </script>
</body>
```
Embora seja tecnicamente possível escrever todo o seu código JavaScript dentro das **script** tags, é considerada uma prática recomendada vincular a um arquivo JavaScript externo. Aqui está um exemplo de uso do **scrip** telemento para vincular a um arquivo JavaScript externo:
```html
<script src="path-to-javascript-file.js"></script>
```
O **src** atributo é usado aqui para especificar o local desse arquivo JavaScript externo.

## Boilerplate e codificação

* **Medelo HTML**: Este é um modelo que inclui a estrutura básica e os elementos essenciasi que todo documento HTML precisa.
```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8" />
    <title>freeCodeCamp</title>
    <link rel="stylesheet" href="./styles.css" />
  </head>
  <body>
    <!--Headings, paragraphs, images, etc. go inside here-->
  </body>
</html>
```
* **DOCTYPE**: Isso é usado para informar aos navegadores qual versão do HTML você está usando.

* **Elemento html**: Representa o elemento de nível superior ou a raiz de um documento HTML. Para especificar o idioma do documento, você deve usar o **lang** atribtuo.

* **Elemento head**: A **head** seção contém metadados importantes, que são informações de bastidores necessárias para navegadores e mecanismos de busca.

* **Elemento meta**:  estes elementos representam os metadados do seu site. Eles contêm detalhes sobre aspectos como codificação de caracteres, como sites como o Twitter devem visualizar o link da sua página e muito mais.

* **Elemento title**:  Este elemento é usado para definir o texto que aparece na aba ou janela do navegador.

* **Codificação de caracteres UTF-8**: UTF-8, ou UCS Transformation Format 8, é uma codificação de caracteres padronizada amplamente utilizada na web. A codificação de caracteres é o método que os computadores usam para armazenar caracteres como dados. O **charset** atributo é usado dentro de um **meta** elemento para definir a codificação de caracteres como UTF-8.

## SEO e compartilhamento social

* **SEO**: Search Engine Optimization é uma prática que otimiza páginas da web para que elas se tornem mais visíveis e tenham uma classificação mais alta nos mecanismos de busca.

* **Elemento Meta (description)**: Usado para fornecer uma breve descrição da página da web e impactar o SEO.

```html
<meta
  name="description"
  content="Discover expert tips and techniques for gardening in small spaces, choosing the right plants, and maintaining a thriving garden."
/>
```

* **Tags Open Graph**:  O protocolo Open Graph permite que você controle como o conteúdo do seu site aparece em várias plataformas de mídia social, como Facebook, LinkedIn e muitas outras.

Ao definir essas propriedades de gráfico aberto, você pode incentivar os usuários a clicarem e interagirem com seu conteúdo. Você pode definir essas propriedades por meio de um conjunto de **meta** elementos dentro da sua **head** seção HTML.

* **Propriedade og:title**: usada para definir o título que será exibido nas postagens de mídia social.
```html
<meta content="freeCodeCamp.org" property="og:title" />
```

* **Propriedade og:type**: A **type**propriedade é usada para representar o tipo de conteúdo compartilhado nas redes sociais. Exemplos desse conteúdo incluem artigos, sites, vídeos ou músicas.
```html
<meta property="og:type" content="website" />
```

* **Propriedade og:image**: usada para definir a imagem exibida nas postagens de mídia social.
```html
<meta
  content="https://cdn.freecodecamp.org/platform/universal/fcc_meta_1920X1080-indigo.png"
  property="og:image"
/>
```

* **Propriedade og:url**: Usada para definir a URL na qual os usuários clicarão para as postagens nas redes sociasi.
```html
<meta property="og:url" content="https://www.freecodecamp.org" />
```

## Elementos de mídia e otimização

* **Elementos substituídos**: Um elemento substituído é um elemento cujo conteúdo é determinado por um recurso externo e não pelo próprio CSS. Um exemplo seria um **iframe** elemento. **iframe** significa "inline frame" (quadro embutido). É um elemento embutido usado para incorporar outro conteúdo HTML diretamente na página HTML.
```html
<iframe src="https://www.example.com" title="Example Site"></iframe>
```
Você pode incluir o **allowfullscreen** atributo que permite ao usuário exibir o iframe em modo de tela cheia.
```html
<iframe
  src="video-url"
  width="width-value"
  height="height-value"
  allowfullscreen
></iframe>
```
Para incorporar um vídeo, **iframe** você pode copiá-lo diretamente de serviços de vídeo populares como YouTube e Vimeo, ou defini-lo você mesmo com o **src** atributo apontando para a URL do vídeo. Veja um exemplo de incorporação de um curso popular do freeCodeCamp do YouTube:

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
Existem outros elementos substituídos, como **video**, e **embed**. E alguns elementos se comportam como elementos substituídos em circunstâncias específicas. Aqui está um exemplo de um **input** elemento com o **type** atributo definido como **image**:
```html
<input type="image" alt="Descriptive text goes here" src="example-img-url">
```
* **Otimização de mídia**: Há três ferramentas a serem consideradas ao usar mídia, como imagens, em suas páginas da web: o tamanho, o formato e a compactação. Um algoritmo de compactação é usado para reduzir o tamanho de arquivos ou dados.

* **Formatos de imagem** :  Dois dos formatos de arquivo mais comuns são PNG e JPG, mas estes não são mais os formatos ideais para exibir imagens. A menos que você precise de suporte para navegadores mais antigos, considere usar um formato mais otimizado, como WEBP ou AVIF.

* **Licenças de imagem**: Uma imagem de domínio público não possui direitos autorais e é livre para uso sem restrições. Imagens licenciadas especificamente sob a licença Creative Commons 0 são consideradas de domínio público. Algumas imagens podem ser disponibilizadas sob uma licença permissiva, como uma licença Creative Commons ou a licença BSD usada pelo freeCodeCamp.

* **SVGs**: Scalable Vector Graphics (Gráficos Vetoriais Escaláveis) rastreiam dados com base em caminhos e equações para plotar pontos, linhas e curvas. O que isso significa é que um gráfico vetorial, como um SVG, pode ser dimensionado para qualquer tamanho sem afetar a qualidade.

## Integração multimídia

* **Elementos  audio e video**: Os elementos **audio** e **video** permitem adicionar conteúdo de som e vídeo aos seus documentos HTML. O **audio** elemento suporta formatos de áudio populares como mp3, wav e ogg. O **video** elemento suporta os formatos mp4, ogg e webm.
```html
<audio src="CrystalizeThatInnerChild.mp3"></audio>
```
Se você quiser ver o player de áudio na página, você pode adicionar o **audio** elemento com o **controls** atributo:
```html
<audio src="CrystalizeThatInnerChild.mp3" controls></audio>
```

O **controls** atributo permite que os usuários gerenciem a reprodução de áudio, incluindo ajuste de volume e pausa ou retomada da reprodução. O **controls** atributo é um atributo booleano que pode ser adicionado a um elemento para habilitar controles de reprodução integrados. Se omitido, nenhum controle será exibido.

* **Atributo loop** : O **loop** atributo é um atributo booleano que faz com que o áudio seja reproduzido continuamente.
```html
<audio
  src="https://cdn.freecodecamp.org/curriculum/js-music-player/can't-stay-down.mp3"
  loop
  controls
></audio>
```

* **Atributo muted**: Quando presente no **audio** elemento, o **muted** atributo booleano iniciará o áudio em um estado silenciado.
```html
<audio
  src="https://cdn.freecodecamp.org/curriculum/js-music-player/can't-stay-down.mp3"
  loop
  controls
  muted
></audio>
```

* **Elemento source**: Quando se trata de tipos de arquivo de áudio, existem diferenças entre os navegadores que suportam cada tipo. Para acomodar isso, você pode usar **source** elementos dentro do **audio** elemento e o navegador selecionará a primeira fonte que entender. Veja um exemplo de uso de vários **source** elementos para um **audioe** lemento:

```html
<audio controls>
  <source src="audio.ogg" type="audio/ogg" />
  <source src="audio.wav" type="audio/wav" />
  <source src="audio.mp3" type="audio/mpeg" />
</audio>
```
Todos os atributos que aprendemos até agora também são suportados no **video** elemento. Aqui está um exemplo de uso de um **video** elemento com os atributos **loop**, **controls** e **muted**:
```html
<video
  src="https://archive.org/download/BigBuckBunny_124/Content/big_buck_bunny_720p_surround.mp4"
  loop
  controls
  muted
></video>
```
* **Atributo poster**: Se você quiser exibir uma imagem durante o download do vídeo, pode usar o **poster** atributo . Este atributo não está disponível para **audio** elementos e é exclusivo do **video** elemento.
```html
<video
  src="https://archive.org/download/BigBuckBunny_124/Content/big_buck_bunny_720p_surround.mp4"
  loop
  controls
  muted
  poster="https://peach.blender.org/wp-content/uploads/title_anouncement.jpg?x11217"
  width="620"
></video>
```

## Tipos de atributos de destino

* **Atributo target**:  Este atributo informa ao navegador onde abrir a URL do elemento âncora. 

* **Valor _self**: Este é o valor padrão para o **target** atributo. Isso abre o link no contexto de navegação atual. Na maioria dos casos, esta será a aba ou janela atual.
```html
<a href="https://freecodecamp.org" target="_self">Visit freeCodeCamp</a>
```

* **Valor _blank**:  Isso abre o link em um novo contexto de navegação. Normalmente, isso abre em uma nova aba. Mas alguns usuários podem configurar seus navegadores para abrir uma nova janela.
```html
<a href="https://freecodecamp.org" target="_blank">Visit freeCodeCamp</a>
```

* **Valor _parent**:  Isso abre o link no contexto pai do contexto atual. Por exemplo, se o seu site tiver um iframe, um **_parent** valor nesse iframe será aberto na aba/janela do seu site, não no frame incorporado.
```html
<a href="https://freecodecamp.org" target="_parent">Visit freeCodeCamp</a>
```

* **Valor _top**: Isso abre o link no contexto de navegação mais alto — pense em "o pai do pai". É semelhante a **_parent**, mas o link sempre abrirá na aba/janela completa do navegador, mesmo para frames incorporados aninhados.
```html
<a href="https://freecodecamp.org" target="_top">Visit freeCodeCamp</a>
```

## Caminhos absolutos vs. relativos

* **Definição de caminho**: Um caminho é uma string que especifica a localização de um arquivo ou diretório em um sistema de arquivos. No desenvolvimento web, caminhos permitem que os desenvolvedores criem links para recursos como imagens, folhas de estilo, scripts e outras páginas da web.

* **Sintaxe de caminho**: Existem três sintaxes principais que você precisa conhecer. A primeira é a barra, que pode ser uma barra invertida ( \) ou uma barra normal ( /), dependendo do seu sistema operacional. A segunda é o ponto simples ( .). E, por fim, temos o ponto duplo ( ..). A barra é conhecida como "separador de caminho". Ela é usada para indicar uma quebra no texto entre nomes de pastas ou arquivos. Um ponto simples aponta para o diretório atual e dois pontos apontam para o diretório pai.
```
public/index.html
./favicon.ico
../src/index.css
```

* **Caminho Absoluto** : Um caminho absoluto é um link completo para um recurso. Ele começa no diretório raiz, inclui todos os outros diretórios e, por fim, o nome do arquivo e a extensão. O "diretório raiz" refere-se ao diretório ou pasta de nível superior em uma hierarquia. Um caminho absoluto também inclui o protocolo — que pode ser **http**, **https**, e **file** o nome de domínio, se o recurso estiver na web. Aqui está um exemplo de um caminho absoluto que leva ao logotipo do freeCodeCamp:
```html
<a href="https://design-style-guide.freecodecamp.org/img/fcc_secondary_small.svg">
  View fCC Logo
</a>
```

* **Caminho Relativo** : Um caminho relativo especifica a localização de um arquivo em relação ao diretório do arquivo atual. Ele não inclui o protocolo nem o nome de domínio, tornando-o mais curto e flexível para links internos dentro do mesmo site. Veja um exemplo de link para a **about.html** página a partir da **contact.html** página original, ambas na mesma pasta:
```html
<p>
  Read more on the
  <a href="about.html">About Page</a>
</p>
```

## Estado de ligação

* **:link**: Este é o estado padrão. Este estado representa um link que o usuário ainda não visitou, clicou ou interagiu. Você pode pensar neste estado como o fornecimento dos estilos base para todos os links da sua página. Os outros estados são baseados nele.

* **:visited**: Isso se aplica quando um usuário já visitou a página vinculada. Por padrão, isso deixa o link roxo, mas você pode usar CSS para fornecer uma indicação visual diferente ao usuário.

* **:hover**: Este estado se aplica quando um usuário passa o cursor sobre um link. Este estado é útil para dar mais atenção a um link, garantindo que o usuário realmente pretenda clicar nele.

* **:focus**: Este estado se aplica quando focamos em um link.

* **:active**: Este estado se aplica a links que estão sendo ativados pelo usuário. Isso normalmente significa clicar no link com o botão esquerdo do mouse, na maioria dos casos.

