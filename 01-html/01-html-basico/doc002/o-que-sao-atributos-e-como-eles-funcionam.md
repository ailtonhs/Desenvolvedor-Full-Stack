# O que são atributos e como eles funcionam?

Um atributo é um valor inserido na tag de abertura de um elemento HTML. Os atributos fornecem informações adicionais sobre o elemento ou especificam como ele deve se comportar.

Aqui está a sintaxe básica de um atributo.
```
<element attribute="value"></element>
```
O nome do atributo é seguido por um sinal de igual (=) e um valor entre aspas. O valor pode ser uma string ou um número, dependendo do atributo.

Vejamos alguns exemplos de atributos HTML comuns. O primeiro exemplo é o **href** atributo, usado para especificar a URL de um link:

```html
<a href="https://www.example-website.com">Visite our website</a>
```

Sem esse atributo, o link não funcionaria, pois não haveria URL de destino. Portanto, você deve icluir esse **href** atributo para que o link funcione.

Outros atributos comuns são o atributo **src**, ou fonte, e **alt**, ou alternativa, que são usados para especificar a fonte de uma imagem e fornecer um texto descritivo alternativo para imagem, respectivamente:

```html
<img src="image.jpg" alt="A beautiful image"/>
```

Semelhante ao **href** atributo, o **src** atributo é obrigatório porque especifica o arquivo de imagem a ser exibido. O **alt** atributo não é obrigatório, mas é recomendado para fins de acessibilidade. Acessibilidade significa garantir que todos, incluindo pessoas com deficiência, possam usar e compreender coisas como sites, aplicativos e espaços físicos.

Alguns atributo são um pouco único em sua sintaxe, como o **checked** atributo mostrado aqui:
```html
<input type="checkbox" checked/>
```
No exemplo a seguir, temos um **input** elemento com o **type** atributo definido como **checkbox**. As entradas são usadas para coletar dados dos usuários, e o **type** atributo especifica o tipo de entrada. Nesse caso, essa entrada é uma caixa de seleção.

O **checked** atributo é usado para especificar que a caixa de seleção deve ser marcada por padrão. O **checked** atributo não requer um valor. Se estiver presente, a caixa de seleção será marcada por padrão. Se o atributo não estiver presente, a caixa de seleçãao será desmarcada. Isso é conhecido como um atributo booleano.

Existem vários atributos booleano comuns que você encontrará em HTML, como **disabled**, **readonly** e **required**. Esses atributos são usados para especificar o estado de um elemento, como se ele está desabilitado, somente leitura ou obrigatório.

O HTML possui muitos atributos que podem ser usados para personalizar o comportamento e a aparência dos elementos em uma página web. Entender como usar atributos é essencial para criar conteúdo web interativo e acessível.