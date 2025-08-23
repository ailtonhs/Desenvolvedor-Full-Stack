# Como exibir endereços em HTML?

O elemento de endereço de contato é usado para representar informações de contato de uma seção de uma página web. O **address** elemento é versátil e pode ser usado em páginas comerciais, páginas de autores, sites pessoais e muito mais.

Ao criar as seções de contato do seu site, você deve usar o **address** elemento semântico em vez de um elemento genérico como um div.

Aqui está um exemplo de uso do **addres** selemento para uma página de contato da empresa:
```html
<address>
  <h2>Company Name</h2>
  <p>
    1234 Elm Street<br />
    Springfield, IL 62701<br />
    United States
  </p>
  <p>Phone: <a href="tel:+15555555555">+1 (555) 555-5555</a></p>
  <p>Email: <a href="mailto:contact@company.com">contact@company.com</a></p>
</address>
```
Neste exemplo, há o nome da empresa, endereço físico, telefone e informações de e-mail. Para o endereço físico, o elemento de quebra de linha, **br**, é usado para mostrar a divisão entre o nome da rua, cidade e país.

Para o número de telefone, temos um elemento âncora com o **href** valor definido para números de telefone. O **tel:+** valor dentro do **href** atributo cria um link clicável para iniciar uma chamada telefônica em determinados dispositivos compatíveis.

Para o endereço de e-mail, outro elemento âncora é usado com o **href** valor definido como um **mailto** link. **mailto** Os links são usados ​​em documentos HTML para permitir que os usuários abram um novo e-mail em seu cliente de e-mail preferido.

Uma das desvantagens de usar um **mailto** link é que os usuários frequentemente o percebem como spam. Infelizmente, muitos spammers usam essa opção para enviar e-mails aos usuários. Portanto, tenha isso em mente ao usá-lo.