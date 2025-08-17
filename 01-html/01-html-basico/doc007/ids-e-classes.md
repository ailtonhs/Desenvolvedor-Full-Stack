# O que são IDs e classes e quando você deve usá-los?

O **id** atributo adiciona um identificador único a um elemento HTML. Neste exemplo, há um **h1** elemento com um **id** **title**:
```html
<h1 id="title">Movie Review Page</h1>
```
Você pode referenciar o **id** nome de **title** em seu JavaScript ou CSS. Aqui está um exemplo de CSS referenciando o **id** nome **title** de para alterar o texto **color** para **red**:
```css
#title {
    color: red;
}
```
O símbolo de hash(#) antes de **title**, informa ao computador que você deseja atingir um **id** com esse valor. Nomes **id** não devem ser usados mais de uma vez e devem ser sempre únicos. Outra coisa a se observar sobre **id** valores é que eles não podem conter espaços. Aqui está um exemplo da aplicação das palavras **main** e **heading** a um **id** valor de atributo:
```html
<h1 id="main heading">Main heading</h1>
```

Os navegadores verão esse espaço como parte do **id** que levará a problemas indesejados em termo de estilo e script. Os **id** valores dos atributos devem conter apenas letras, dígitos, sublinhados e traços.

Ao contrário do **id** atributo, o **class** valor do atributo não precisa ser único e pode conter espaços. Aqui está um exemplo de aplização de uma classe chamada **box** a um **div** elemento:
```html
<div class="box"></div>
```

Se você quiser adicionar vários nomes de classes a um elemento, pode fazê-lo separando-os por um espaço. Aqui está um exemplo atualizado aplicado várias classes a um **div** elemento:
```html
<div class="box red-box"></div>
```
Para aplicar um conjunto de estilos a essa **box** classe, você pode referenciá-la dentro do seu CSS. Aqui está um exemplo de configuração das propriedades **width**, **height** e **border** para o elemento com o **class** nome **box**:

```css
.box {
    width: 200px;
    height: 200px;
    border: 2px solid black;
}
```
O símbolo de ponto (.) antes de **box**, informa ao computador que você deseja atingir um **class** com esse valor. Quando o código for executado, ele pesquisará em todo o seu documento HTML para encontrar todos os elementos com esse nome de classe e aplicará esses estilos.

Então, recapitulando, quando você deve usar **id** ou **class**? As classes são mais indicadas quando você deseja aplicar um conjunto de estilos a vários elementos. Se você deseja atingir um elemento específico, é melhor usar, **id** pois esses valores precisam ser únicos.