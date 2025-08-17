# Qual é a função do elemento Script em HTML e como ele pode ser usado para vincular arquivos JavaScript externos?

O **script** elemento é usado para incorporar código executável. A maioria dos desenvolvedores o utiliza para executar código JavaScript. O JavaScript é usado para adicionar interatividade às suas páginas web. Exemplos comuns de uso de JavaScript incluem jogos interativos, controles deslizantes de imagens e formulários dinâmicos que validam a entrada do usuário em tempo real. Aqui está um exemplo de uso do **script** elemento em um documento HTML:

```html
<body>
    <script>
        alert("Welcome to freeCodeCamp");
    </script>
</body>
```
Neste exemplo, temos um **alert** para exibir a mensagem **"Welcome to freeCodeCamp"**. Quando a página carregar pela primeira vez, o alerta aparecerá. O usuário pode então clicar no botão OK para descartar a mensagem.

Embora seja tecnicamente possível escrever todo o seu código JavaScript entro das **script** tags, é considerada uma prática recomendada vincular a um arquivo JavaScript externo. Aqui está um exemplo de uso do **script** elemento para vincular a um arquivo JavaScript externo:

```html
<script src="path-to-javascript-file.js"></script>
```
O **src** atributo é usado aqui para especificar o local para o arquivo JavaScript externo. **src** significa "fonte". A razão pela qual não é recomendado colocar todo o seu JavaScript dentro do documento HTML é a separação de interesses. A separação de interesses é um principio de design que divide seus programas em seções distintas e faz com que cada seção aborde um interesse específico. Neste caso, queremos separar nosso código JavaScript do nosso código HTML.