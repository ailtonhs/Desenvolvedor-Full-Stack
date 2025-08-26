# Quais são os diferentes tipos de botões e quando você deve usá-los?

O **button** elemento é usado para executar uma ação específica quando ativado. Aqui está um exemplo de um **button** elemento com o texto do botão **Start Game**.
```html
<button>Start Game</button>
```
Outros exemplos de uso do **button** elemento incluem o envio de um formulário, a exibição de um modal ou a alternância entre abrir e fechar um menu lateral. O **button** elemento possui um **type** atributo que controla o comportamento do botão quando ele é ativado. O primeiro valor possível para o **type** atributo seria o **button** tipo. Aqui está um exemplo de uso do **button** elemento com o **button** tipo e o texto **Show Alert**:
```html
<button type="button">Show Alert</button>
```
Por padrão, o botão não fará nada quando ativado. No entanto, você pode adicionar algum código JavaScript para torná-lo interativo, como exibir um alerta neste caso. Outro valor possível para o **type** atributo é o **submit** valor. Aqui está um exemplo de uso de um **button** elemento com o **submit** tipo:
```html
<form action="">
  <label for="email">Email address:</label>
  <input type="email" id="email" name="email" />
  <button type="submit">Submit form</button>
</form>
```
Dentro deste **form** elemento, há um elemento **label** e **input** para o endereço de e-mail do usuário. Quando o usuário clica no botão de envio, seus dados são enviados ao servidor e processados. O terceiro valor possível para o **type** atributo é o **reset** valor. Aqui está um exemplo de um **form** elemento com botões de redefinição e envio:
```html
<form action="">
  <label for="email">Email address:</label>
  <input type="email" id="email" name="email" />
  <button type="reset">Reset form</button>
  <button type="submit">Submit form</button>
</form>
```
Neste exemplo modificado, os elementos **label** e **input** são usados ​​para coletar o endereço de e-mail do usuário. Quando o usuário clica no botão de redefinição, todos os seus dados inseridos são apagados. É importante observar que botões de redefinição geralmente não são a melhor ideia, pois podem levar os usuários a redefinirem seus dados acidentalmente. Além disso, vários botões no seu formulário podem sobrecarregar a interface do usuário.

Outra maneira de criar botões em HTML é usar o **input** elemento . O **input** elemento também possui um **type** atributo com os valores possíveis de **submit**, **resete**  **button**. Aqui está um exemplo de uso do **input** elemento com o **type** definido como **button**:
```html
<input type="button" value="Show Alert" />
```
O **value** atributo é usado para exibir o texto do botão. Então, qual é a diferença entre usar os elementos **input** e **button** ? Os elementos **input** são elementos vazios, o que significa que não podem ter nós filhos, como texto, e podem ter apenas uma tag inicial. Por outro lado, o elemento **button** oferece mais flexibilidade, pois você pode aninhar texto, imagens e ícones dentro dele.