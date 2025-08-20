# Qual é a diferença entre caminho absolutos e relativos?

Um caminho é uma string que especifica a localização de um arquivo ou diretório em um sistema de arquivos. No desenvolvimento web, caminhos permitem que os desenvolvedores criem links para recursos como imagens, folhas de estilo, scripts e outras páginas da web. Existem caminhos absolutos e relativos - ambos são essenciais ao especificar a localização de arquivos em um sistema de arquivos. Vamos analizar os dois para que você possa decidir qual usar e quando.

Um caminho absoluto é um link completo para um recurso. Ele começa no diretório raiz, inclui todos os outros diretórios e, por fim, o nome do arquivo e a extersão. O "diretório raiz" refere-se ao diretório ou pasta de nível superior em uma hierarquia.

Um caminho absoluto também inclui o protocolo - que pode ser **http**, **https**, e **file** o nome de domínio, se o recurso estiver na web. Aqui está um exemplo de um caminho absoluto que leva ao logotipo do freeCodeCamp:

```html
<a href="https://design-style-guide.freecodecamp.org/img/fcc_secondary_small.svg">
  View fCC Logo
</a>
```
Neste exemplo, o protocolo é **https**, o nome de domínio é **design-style-guide.freecodecamp.org** e o nome do arquivo é **fcc_secondary_small.svg**.

Agora, e se o recurso ao qual você deseja vincular usando um caminho absoluto estiver na sua máquina local? Veja como vincular o **about.html** arquivo usando um caminho absoluto:

```html
<p>
  Read more on the
  <a
    href="/Users/user/Desktop/fCC/script-code/absolute-vs-relative-paths/pages/about.html"
    >About Page</a
    >
</p>
```
Parece assim porque estamos entrando em uma pasta chamada **Users**, depois em uma pasta chamada **user**, depois em uma pasta chamada **Desktop**, depois em uma pasta chamada **FCC**, depois em uma pasta chamada **script-code**, depois em uma pasta chamada **absolute-vs-relative-paths**, depois em uma pasta chamada **pages** para finalmente obter o **about.html** arquivo.

Veja como fica o URL absoluto na barra de endereços do navegador:
```
file:///Users/user/Desktop/fCC/script-code/absolute-vs-relative-paths/pages/about.html
```

A URL inclui o protocolo, **file://**. Também inclui o caminho, que se parece com isto: **/Users/user/Desktop/FCC/script-code/absolute-vs-relative-paths/pages/**, e representa a série de pastas que levam ao arquivo. E, por fim, também inclui o **about.html**, que é o nome do arquivo e a extensão.


Agora, vamos analizar o caminho relativo. Um caminho relativo especifica a localização de um arquivo em relação ao diretório do arquivo atual. Ele não inclui o protocolo nem o nome de domínio, o que o torna mais curto e flexível para links internos dentro do mesmo site. Aqui está um exemplo de link para a **about.html** página a partir da **contact.html** página, ambas na mesma pasta:

```html
<p>
  Read more on the
  <a href="about.html">About Page</a>
</p>
```
Imagine que você está na **contact.html** página e, como **about.html** ela está no mesmo lugar, você simplesmente obtém o nome do arquivo. Este é um exemplo de uso de um caminho de arquivo relativo.

Então, qual você deve usar e quando: um caminho absoluto ou caminho relativo? Aqui estão as regras que você deve seguir:

* Use caminhos absolutos ao criar um link para um recurso hospedado em um site externo.

* Use caminho absolutos quando precisar que o link para uma página ou recurso funcione de forma consistente, independentemente da localização do documento no site

* use caminho relativos ao criar links para recursos dentro do mesmo site.

* Use caminho relativos se quiser manter seu código mais liimpo e fácil de manter durante o desenvolvimento.

* Use caminhos relativos durantes testes locais para garantir que os links funcionem sem uma conexão com a internet.
