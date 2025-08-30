# Revisão de tabelas e formulários HTML

## Elem
entos e atributos de formulário HTML

* **Elementoo form**: Usado para criar um formulário HTML para entrada do usuário

* **Atributo action**: Usado para especificar a URL para onde os dados do formuário devem ser enviados.

* **Atributo method**: Usado para especificar o método HTTP a ser usado ao enviar os dados do formulário. Os métodos mais comuns são **GET** e **POST**.
```html
<form method="value-goes-here" action="url-goes-here">
  <!-- inputs go inside here -->
</form>
```

* **Elemento input**: Usado para criar um campo de entrada para entrada do usuário.

* **Atributo type**: Usado para especificar o tipo de campo de entrada. Ex.: **text**, **email**, **number**, **radio**, **checkbox**, etc.

* **Atributo placeholder**: Usado para mostrar uma dica ao usuário sobre o que inserir no campo de entrada.

* **Atributo value**: Usado para especificar o valor da eentrada. Se a entrada tiver um **button** tipo, o **value** atributo pode ser usado para definir o texto do botão.

* **Atributo name**: Usado para atribuir um nome a um campo de entrada, que serve como chave quando os dados do formulário são enviados. Para botões de opção, atribuir o mesmo nome **name** agrupa-os, de forma que apenas uma opção do grupo possa ser selecionada por vez.

* **Atributo size**: Usado para definir o número de caracteres que devem ficar visíveis quando o usuário digita na entrada.

* **Atributo min**: Pode ser usado com tipos de entrada, como **number** para especificar o valor mínimo permitido no campo de entrada.

* **Atributo max**: Pode ser usado com tipos de entrada, como **number** para especificar o valor máximo permitido no campo de entrada.

* **Atributo minlength**:  Usado para especificar o número mínimo de caracteres necessários em um campo de entrada.

* **Atributo maxlength**: Usado para especificar o número máximo de caracteres permitidos em um campo de entrada.

* **Atributo required**: Usado para especificar que um campo de entrada deve ser preenchido antes de enviar o formulário.

* **Atributo disabled**: Usado para especificar que um campo de entrada deve ser desabilitado.

* **Atributo readonly**: Usado para especificar que um campo de entrada é somente leitura.
```html
<!-- Text input -->
<input 
  type="text"
  id="name"
  name="name"
  placeholder="e.g. Quincy Larson" 
  size="20"
  minlength="5"
  maxlength="30"
  required
/>

<!-- Number input -->
<input 
  type="number"
  id="quantity"
  name="quantity"
  min="2"
  max="10"
  disabled
/>

<!-- Button -->
<input type="button" value="Show Alert" />
```

* **Elemento label**:  Usado para criar um rótulo para um campo de entrada.

* **Atributo for**:  Usado para especificar para qual campo de entrada o rótulo se destina.

* **Associação de forma implícita**: As entradas podem ser associadas a rótulos envolvendo o campo de entrada dentro do labelelemento.
```html
<form action="">
  <label>
    Full Name:
    <input type="text" />
  </label>
</form>
```

* **Associação de forma explícita**: Entradas podem ser associadas a rótulos usando o **for** atributo no **label** elemento.
```html
<form action="">
  <label for="email">Email Address: </label>
  <input type="email" id="email" />
</form>
```

* **Elemento button**: Usado para criar um botão clicável. Um botão também pode ter um **type** atributo, que é usado para controlar o comportamento do botão quando ele é ativado. Ex.: **submit**, **reset**, **button**.
```html
<button type="button">Show Form</button>
<button type="submit">Submit Form</button>
<button type="reset">Reset Form</button>
```

* **Elemento fieldset**: Usado para agrupar entradas relacionadas.

* **Elemento legend**: Usado para adicionar uma legenda para descrever o grupo de entradas.
```html
<!-- Radio group -->
<fieldset>
  <legend>Was this your first time at our hotel?</legend>

  <label for="yes-option">Yes</label>
  <input id="yes-option" type="radio" name="hotel-stay" value="yes" />

  <label for="no-option">No</label>
  <input id="no-option" type="radio" name="hotel-stay" value="no" />
</fieldset>

<!-- Checkbox group -->
<fieldset>
  <legend>
    Why did you choose to stay at our hotel? (Check all that apply)
  </legend>

  <label for="location">Location</label>
  <input type="checkbox" id="location" name="location" value="location" />

  <label for="price">Price</label>
  <input type="checkbox" id="price" name="price" value="price" />
</fieldset>
```

**Estado focado**: Este é o estado de um campo de entrada quando ele é selecionado pelo usuário.

## Trabalhando com elementos e atributos de tabela HTML

* **Elemento de tabela**: Usado para criar tabela HTML.

* **Elemento Table Head (thead)**: Usado para agrupar o conteúdo do cabeçalho em uma tabela HTML.

* **Elemento Table Row (tr)**: Usado para criar uma linha em uma tabela HTML.

* **Elemento Table Header (th)**: Usado para criar uma célula de cabeçalho em uma tabela HTML.

* **Elemento do corpo da tabela (tbody)**: Usado para agrupar o conteúdo do corpo em uma tabela HTML.

* **Elemento Table Date Cell (td)**: Usado para criar uma célula de dados em uma tabel HTML.

* **Elemento Table Foot (tfoot)**: Usado para agrupar o conteúdo do rodapé em uma tabela HTML.

* **Elemento caption**: Usado para adicionar um título de uma tabela HTML.

* **Atributo colspan**: Usado para especificar o número de colunas que uma célula da tabela deve abranger.
```html
<table>
  <caption>Exam Grades</caption>

  <thead>
    <tr>
      <th>Last Name</th>
      <th>First Name</th>
      <th>Grade</th>
    </tr>
  </thead>

  <tbody>
    <tr>
      <td>Davis</td>
      <td>Alex</td>
      <td>54</td>
    </tr>

    <tr>
      <td>Doe</td>
      <td>Samantha</td>
      <td>92</td>
    </tr>

    <tr>
      <td>Rodriguez</td>
      <td>Marcus</td>
      <td>88</td>
    </tr>
  </tbody>

  <tfoot>
    <tr>
      <td colspan="2">Average Grade</td>
      <td>78</td>
    </tr>
  </tfoot>
</table>
```
## Trabalhando com ferramentas HTML

* **Validador HTML**: Uma ferramenta que verifica a sintaxe do código HTML para garantir que ele seja válido.

* **Inspetor DOM**: Uma ferramenta que permite inspecionar e moodificar a estrutura HTML de uma página web.

* **Devtools**: Um conjunto de ferramentas para desenvolvedores web incorporadas diretamente no navegador que ajudam você a depurar, criar perfis e analisar páginas da web.