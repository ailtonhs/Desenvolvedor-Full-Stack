# Revisão de HTML semântico

## Importância do HTML Semântico
* **Hierarquia estrutural para elementos de título**: É importante usar o elemento de título correto para manter a hierarquia estrutural do conteúdo. O **h1** elemento é o nível mais alto do título e o **h6** elemento é o nível mais baixo.

* **Elementos HTML de apresentação**: Elementos que definem a aparência do conteúdo. EX.: os elementos obsoletos **center**, **big** e **font**.

* **Elementos semânticos HTML** Elementos que contêm significado e estrutura. Ex.: **header**, **nav**, **figure**.


## Elementos HTML Semânticos
* **Elemento de cabeçalho**: Usado para definir o cabeçalho de um documento ou seção.

* **Elemento principal**: Usado para conter o conteúdo principal da página web.

* **Elemento de seção**: Usado para dividir o conteúdo em seções menores.

* **Elemento Navigation Section (nav)**: Representa um seção com links de navegação.

* **Elemento figura**: Usado para conter ilustrações e diagramas.

* **Elemento de ênfase (em)**: Marca o texto que tem ênfase acentuada.
```html
<p>
  Never give up on <em>your</em> dreams.
</p>
```

* **Elemento de texto idiomático (i)**: Usado para destacar voz ou humor alternativo, termos idiomáticos de outro idioma, termos técnicos e pensamentos.
```html
<p>
  There is a certain <i lang="fr">je ne sais quoi</i> in the air.
</p>
```
O **lang** atributo da tag **i** é usado para especificar o idioma do conteúdo. Neste caso, o idioma seria francês. O **i** elemento não indica se o texto é importante ou não, apenas mostra que ele é de alguma forma diferente do texto ao redor.

* **Elemento de forte importancia (strong)**: Marca o texto que tem forte importância.
```html
<p>
  <strong>Warning:</strong> This product may cause allergic reactions.
</p>
```

* **Elemento "Trazer Atenção para" (b)**: Usado para chamar a atenção para um texto que não é importante para o significado do conteúdo. É comumente usado para destacar palavras-chave em resumos ou nomes de produtos em avaliações.
```html
<p>
  We tested several products, including the <b>SuperSound 3000</b> for audio quality, the <b>QuickCharge Pro</b> for fast charging, and the <b>Ecoclean Vacuum</b> for cleaning. The first two performed well, but the <b>Ecoclean Vacuum</b> did not meet expectations.
</p>
```

* **Elemento Lista de Descrição(dl)**: Usado para representar uma lista de agrupamentos de termos-descrição.

* **Elemento Descrição Termo (dt)**: Usado para representar o termo que está sendo definido.

* **Elemento Detalhes da Descrição (dd)**: Usado para representar a descrição do termo.
```html
<dl>
  <dt>HTML</dt>
  <dd>HyperText Markup Language</dd>
  <dt>CSS</dt>
  <dd>Cascading Style Sheets</dd>
</dl>
```

* **Elemento de Citação em Bloco (blockquote)**: Usado para representar um seção citada de outra fonte. Este elemento possuim um **cite** atributo. O valor do **cite** atributo é a URl da fonte.
```html
<blockquote cite="https://www.freecodecamp.org/news/learn-to-code-book/">
  "Can you imagine what it would be like to be a successful developer? To have built software systems that people rely upon?"
</blockquote>
```

* **Elemento Citação (cite)**: usado para atribuir visualmente a fonte da obra referenciada. Marca o título da referência.
```html
<div>
  <blockquote cite="https://www.freecodecamp.org/news/learn-to-code-book/">
    "Can you imagine what it would be like to be a successful developer? To have built software systems that people rely upon?"
  </blockquote>
  <p>
    -Quincy Larson, <cite>How to learn to Code and Get a Developer Job [Full Book].</cite>
  </p>
</div>
```

* **Elemento Inline Quotation (q)**: Usado para representar uma citação curta inline.
```html
<p>
  As Quincy Larson said,
  <q cite="https://www.freecodecamp.org/news/learn-to-code-book/">
    Momentum is everything.
  </q>
</p>
```
* **Elemento Abreviação (abbr)**: Usado para representar uma abreviação ou sigla. Para ajudar os usuários a entender o que é a abreviação ou sigla, você pode mostrar sua forma completa, uma descrição legível por humanos, com o **title** atributo.
```html
<p>
  <abbr title="HyperText Markup Language">HTML</abbr> is the foundation of the web.
</p>
```

* **Elemento Endereço de contato (address)**: Usando para representar as informações de contato.

* **Elemento de Data Hora (time)**: Usado para representar uma data e/ou hora. O **datetime** atributo é usado para traduzir datas e horas para um formato legível por máquina.
```html
<p>
  The reservations are for the <time datetime="20:00">20:00 </time>
</p>
```
* **atributo datetime ISO 8601**: Usado para representar datas e horas em um formato legível por máquina. O formato padrão é **YYYY-MM-DDThh:mm:ss**, com a letra maiúscula **T** como separador entre a data e a hora.

* **Elemento sobrescrito (sup)**: Usado para representar texto sobrescrito. Casos de uso comuns para o **sup** elemento incluem expoentes, letras maiúsculas e números ordinais.
```html
<p>
  2<sup>2</sup> (2 squared) is 4.
</p>
```

* **Elementoo Subscrito (sub)**: Usado para representar texto subscrito. Casos de uso comuns para o elemento subscrito incluem fórmulas químicas, notas de rodapé e subscritos variáveis.
```html
<p>
  CO<sub>2</sub>
</p>
```

* **Elemento Inline (code)**: Usado para representar um fragmento de código de computador.
* **Elemento de texto pré-formatado (pre)**: representa texto pré-formatado.
```html
<pre>
  <code>
    body {
      color: red;
    }
  </code>
</pre>
```

* **Elemento Unarticulated Annotation (u)**: Usado para representar um intervalo de texto embutido que deve ser renderizado de uma forma que indique que tem uma anotação não textual.
```html
<p>
  You can use the unarticulated annotation element to highlight
  <u>inccccort</u> <u>spling</u> <u>issses</u>.
</p>
```

* **Elemento Ruby Annotation (ruby)**: usado para anotar texto com explicações de pronúncia ou significado. Um exemplo de uso é para tipografia do Leste Asiático.
* **Elemento parêntesis de fallback do Ruby(rp)**: usado como fallback para navegadores que não têm suporte para exibir anotações do Ruby.
* **Elemento de texto Ruby (rt)**: usado para indicar texto para a anotação Ruby. Geralmente usado para pronúncia ou detalhes de tradução na tipografia do Leste Asiático.
```html
<ruby>
  明日 <rp>(</rp><rt>Ashita</rt><rp>)</rp>
</ruby>
```

* **Elemento tachado (s)**: usado para representar conteúdo que não é mais preciso ou relevante.
```html
<p>
  <s>Tomorrow's hike will be meeting at noon.</s>
</p>
<p>
  Due to unforeseen weather conditions, the hike has been canceled.
</p>
```