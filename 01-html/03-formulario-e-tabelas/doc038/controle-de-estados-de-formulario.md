# Quais são os diferentes estados de forma e por que eles são importantes?

Em HTML, os controles de formulário, assim como as entradas, podem estar em diferentes estágios ou condições, como **focused** estado, **readonly** estado ou **disabled** estado.

O primeiro estado seria considerado o **default** estado. O estado padrão de uma entrada de endereço de e-mail é uma entrada em branco. É assim que a entrada de e-mail se parece quando é renderizada pela primeira vez na página. Nesse ponto, o usuário não inseriu nenhuma informação.

Quando o usuário clica em um controle de formulário ou o seleciona com a tecla Tab do teclado, isso significa que ele está nesse **focused** estado. Quando uma entrada está nesse **focused** estado, a maioria dos navegadores exibe uma borda azul destacada ao redor da entrada. Mas você pode optar por adicionar estilos adicionais em CSS.

Outro estado de formulário é o **disabled** estado. Este estado mostra aos usuários que uma entrada não pode ser focalizada ou ativada. Para desabilitar uma entrada, você pode adicionar o **disabled** atributo booleano ao elemento, assim:
```html
<input disabled type="email" name="email" id="email" />
```
Se o usuário tentar clicar na entrada, o foco não será habilitado. Semelhante ao **focused** estado, você pode optar por adicionar estilos adicionais ao **disabled** estado usando CSS.

Outro tipo de estado de formulário é o **readonly** estado. Isso ocorre quando um controle de formulário, como uma entrada, não é editável pelo usuário. Aqui está um exemplo de como definir uma entrada de e-mail como somente leitura:
```html
<input
  readonly
  type="email"
  name="email"
  id="email"
  value="example@email.com"
/>
```
O **value** atributo é usado para definir o valor exibido dentro do campo de entrada. Se você tentasse clicar na entrada, não conseguiria editar o valor existente.

Uma diferença fundamental entre o **disabled** estado e **readonly** o estado é que um **readonly** pode ser focado, enquanto o **disabled** estado não.

Entender os diferentes estados do formulário é importante porque eles garantem uma experiência tranquila ao usuário, fornecendo feedback e orientação claros durante o tratamento de erros.

