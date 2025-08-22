# Qual é a diferença entre HTML apresentacional e semântico?

O HTML apresentacional foca na aparência e no estilo do conteúdo. Nos primórdios do HTML, os desenvolvedores usavam elementos como **center**, **big** e **font**. Mas, no desenvolvimento web moderno, você não deve usar esses tipos de elementos devido às suas limitações e ao impacto negativo na acessibilidade e na manutenibilidade.

Muitos elementos HTML de apresentação estão obsoletos, o que significa que estão desatualizados e não são mais recomendados. Existem maneiras melhores de obter os mesmos resultados. No entanto, é útil saber que elas existem, então vamos dar uma olhada em alguns exemplos.

O **font** elemento é um elemento obsoleto usado para definir o tamanho da fonte e a cor do texto. Veja um exemplo de um **font** elemento:
```html
<font size="5" color="blue">This text is blue and large.</font>
```
Este exemplo define a cor do texto como **blue** e o tamanho como um valor de **5**. O intervalo para o **size** atributo é de **1** a **7**, sendo , **1** sendo , o menor e **7**, o maior. O valor padrão é **3**, se você não definir o valor explicitamente.

Embora esse elemento ainda funcione, você não deve usá-lo porque o tamanho e a cor da fonte devem sempre ser definidos em CSS, não em HTML.

O **cente** relemento é outro elemento obsoleto usado para centralizar o conteúdo horizontalmente dentro de seu contêiner. Veja um exemplo do **center** elemento que contém texto e um elemento de parágrafo:
```html
<center>
  This text is centered.
  <p>HTML is awesome.</p>
</center>
```

No navegador, você verá todo o conteúdo dentro do **center** elemento centralizado horizontalmente.

E em seguida, temos o **big** elemento. Este é outro elemento HTML de apresentação obsoleto que torna o texto incluso um nível maior que o texto ao redor. Aqui temos um exemplo que define um parágrafo com duas partes:
```html
<p>
  This text has a normal font size.
  <big>This text is larger.</big>
</p>
```
A primeira parte tem texto em tamanho normal, enquanto a segunda parte contida no **big** elemento será exibida em um tamanho de fonte maior. No navegador, você verá que o texto dentro do **big** elemento parece maior em comparação com o texto ao redor.

No entanto, lembre-se de que o tamanho da fonte deve sempre ser definido com CSS, portanto, você não deve usar esse elemento em HTML moderno.

Estes foram exemplos de elementos HTML de apresentação. Mas todos eles estão obsoletos e não são mais recomendados. Então, o que você deve usar no lugar? Vamos ver.

O HTML semântico agora é a prática recomendada. Ele descreve o conteúdo dos elementos, tornando-o muito mais fácil de ler, entender e manter.

Os mecanismos de busca podem entender facilmente seu site quando você usa HTML semântico. Também é útil para fins de acessibilidade, pois os leitores de tela precisam de informações semânticas para descrever o que está na página.

### Exemplos de elementos HTML semânticos incluem:

* O elemento **header** para definir o cabeçalho do documento ou seção.

* O elemento da seção de navegação, **nav**, para seções com links de navegação.

* O elemento **section** para agrupar informações relacionadas.

* O elemento **figure** para ilustrações e diagramas.

Este é um exemplo de um **header** elemento que contém um elemento de seção de navegação:
```html
<header>
  <nav>
    <a href="#">Home</a>
    <a href="#">About</a>
    <a href="#">Contact</a>
  </nav>
</header>
```

Os elementos semânticos demonstram claramente sua finalidade dentro da estrutura HTML. Existem muitos elementos semânticos HTML diferentes. Você certamente encontrará um que atenda às necessidades do seu projeto.

Ótimo trabalho. Agora você sabe a diferença entre HTML de apresentação e HTML semântico: o HTML semântico descreve o conteúdo, enquanto o HTML de apresentação foca na aparência.

