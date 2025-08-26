# O que é validação de formulário do lado do cliente em formulários HTML e quais são alguns exemplos?

Quando um usuário preenche um formulário em seu site, é importante que ele preencha todas as informações necessárias no formato correto. Os controles de formulário HTML, assim como as entradas, possuem diversas validações integradas que você pode usar para verificar se há dados inválidos. Isso ajudará a garantir que o usuário corrija esses erros antes que as informações sejam enviadas e processadas pelo servidor.

O termo "lado do cliente" refere-se a tudo o que acontece no computador ou dispositivo do usuário, como a parte de um site ou aplicativo com a qual você interage diretamente. Isso inclui o layout, o design e quaisquer recursos interativos.

O termo "lado do servidor" refere-se a tudo o que acontece no servidor, no computador ou sistema que hospeda o site ou aplicativo. Isso inclui o processamento de dados, a execução de aplicativos e o processamento de solicitações provenientes do dispositivo do usuário.

Embora a validação do lado do cliente seja importante, você também precisa da validação do lado do servidor para maior segurança. Usuários mal-intencionados podem contornar as verificações do lado do cliente, portanto, medidas robustas do lado do servidor são essenciais. Você aprenderá mais sobre isso em um módulo posterior. Por enquanto, vamos dar uma olhada em alguns exemplos de validação de formulários do lado do cliente.

Um exemplo comum de validação de formulário integrada é usar o **required** atributo em entradas. O **required** atributo especifica que o usuário precisa preencher aquela parte do formulário antes que ele seja enviado. Aqui está um exemplo de uso do **required** atributo em uma entrada de e-mail:
```html
<form action="">
  <label for="email">Email Address (Required field):</label>
  <input required type="email" name="email" id="email" />
  <button type="submit">Submit Form</button>
</form>
```
Quando o usuário clicar no **Submit** botão sem fornecer um endereço de e-mail, ele será alertado de que o campo é obrigatório e o formulário não será enviado. Cada navegador terá seu próprio conjunto de estilos para exibir essa mensagem de alerta.

Outra vantagem de usar a entrada de e-mail é que as entradas de e-mail possuem alguma validação básica para garantir endereços de e-mail formatados corretamente. Por exemplo, se você digitar palavras aleatórias e clicar em "Enviar", o navegador exibirá um alerta informando que um **@** sinal está faltando. É importante observar que os navegadores verificam apenas a validação básica para endereços de e-mail padrão. Cabe a você adicionar camadas adicionais de validação, sobre as quais aprenderá em módulos posteriores.

Outras formas de validação para entradas de e-mail incluem o uso dos atributos **minlength** e **maxlength**. Aqui está um exemplo usando a validação adicional:
```html
<form action="">
  <label for="email">Email Address (Required field):</label>
  <input
    required
    type="email"
    name="email"
    id="email"
    minlength="4"
    maxlength="64"
  />
  <button type="submit">Submit Form</button>
</form>
```
Os atributos **minlength** e **maxlength** são usados ​​para definir o comprimento mínimo e máximo em caracteres para a entrada de e-mail. Se você não incluir o comprimento mínimo ou exceder o comprimento máximo de caracteres, o navegador exibirá uma mensagem de alerta.

