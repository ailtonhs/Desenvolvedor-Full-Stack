# Como exibir abreviações e siglas em HTML?

Uma abreviação é uma forma abreviada de uma palavra. Por exemplo, "Dr." seguido de um ponto final é uma abreviação da palavra "doutor".

Pegando as primeiras letras de cada palavra H, T, M e L, você obtém a sigla HTML. Ambas são muito úteis para escrever textos mais concisos, especialmente quando são bem conhecidas e fáceis de entender em um determinado contexto.

Se você precisa exibir abreviações e siglas em HTML, o elemento abbreviation é exatamente o que você procura. Você deve sempre explicar o significado completo delas ao usá-las pela primeira vez. Depois, você pode usar o elemento abbreviation para destacá-las e fornecer mais detalhes.

Aqui está um exemplo onde você pode ver um parágrafo com a frase **HTML is the foundation of the web**:
```html
<p><abbr>HTML</abbr> is the foundation of the web.</p>
```
A sigla HTML está dentro de um elemento de abreviação. No navegador, você verá que nada mudou. Ainda parece texto normal. O elemento de abreviação fornece um contexto útil nos bastidores, mas os usuários ainda verão a sigla como texto normal.

Se você quiser ajudar os usuários a entender o que essa sigla significa, você pode mostrar sua forma completa com o **title** atributo.

O **title** atributo é opcional, mas se você decidir incluí-lo, ele deve ser uma descrição legível da abreviação ou sigla.

Vamos pegar o mesmo exemplo anterior, mas adicionar o **title** atributo . Será **HyperText Markup Language**, a forma expandida da sigla:
```html
<p><abbr title="HyperText Markup Language">HTML</abbr> is the foundation of the web.</p>
```
Normalmente, o estilo do elemento de abreviação muda quando você adiciona este atributo. O estilo específico depende do navegador. Alguns navegadores podem exibir um sublinhado pontilhado, enquanto outros podem converter o conteúdo para versalete ou até mesmo atribuir certos estilos padrão, como um sublinhado pontilhado. Quando o usuário passa o mouse sobre a sigla, o formato completo é exibido como uma dica de ferramenta.

Embora você não precise necessariamente usar o elemento de abreviação para cada abreviação ou acrônimo em sua página da web, ele é recomendado para aqueles que podem não estar claros e para aqueles que podem precisar de contexto adicional.

Você deve usar seu bom senso para encontrar o equilíbrio certo entre informação e apresentação para evitar desorganizar o texto e, ao mesmo tempo, ser claro e conciso.

