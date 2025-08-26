# Como funcionam formulários, rótulos e entradas em HTML?

O **form** elemento em HTML é usado para coletar informações do usuário, como nomes e endereços de e-mail. Aqui está um exemplo de um formelemento:
```html
<form action="url-goes-here">
  <!-- input elements go here -->
</form>
```

O **action** atributo especifica para onde os dados do formulário serão enviados após o envio. Para coletar informações específicas, como nomes e endereços de e-mail, você usaria o inputelemento. Veja um exemplo de uso de um inputelemento:
```html
<form action="">
  <input type="text" />
</form>
```
Os **input** elementos são elementos vazios e não possuem tags de fechamento. O **type** atributo define o tipo de dado esperado do usuário. Nesse caso, os dados seriam texto simples. Para adicionar um rótulo à entrada, você usaria um **label** elemento. Aqui está um exemplo de uso de um **label** elemento com o texto de Full Name:
```html
<form action="">
  <label>
    Full Name:
    <input type="text" />
  </label>
</form>
```

Ao aninhar um **input** dentro de um **label** elemento, você cria uma associação implícita entre o **label** e o **input** campo. O termo "implícito" refere-se a algo que é compreendido ou inferido sem precisar ser explicitamente declarado ou definido com atributos ou elementos adicionais. Para associar explicitamente um **label** a um **input**, você pode usar o **for** atributo . Aqui está um exemplo de uso do **for** atributo para um rótulo de endereço de e-mail:
```html
<form action="">
  <label for="email"> Email Address: </label>
  <input type="email" id="email" />
</form>
```
Ao usar uma associação explícita, os valores dos **for** atributos e **id** precisam ser os mesmos. Nesse caso, ambos os valores são definidos como **email**. O **email** tipo na entrada fornece validação básica para endereços de e-mail formatados corretamente. Se você quiser mostrar dicas adicionais aos usuários sobre a entrada esperada, pode usar o **placeholder** atributo. Aqui está um exemplo usando o **placeholder** atributo dentro da entrada de e-mail:
```html
<form action="">
  <label for="email"> Email Address: </label>
  <input type="email" id="email" placeholder="Ex. example@email.com" />
</form>
```
Para o texto de espaço reservado, você deve fornecer um texto curto e útil para mostrar o formato e o tipo de dados que espera dos seus usuários. Nesse caso, o texto de espaço reservado, **Ex. example@email.com**, indica ao usuário que ele deve inserir um endereço de e-mail com o formato correto.