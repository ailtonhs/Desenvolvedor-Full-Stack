# O que são listas de descrição e quando você deve usá-las?

Listas de descrições são perfeitas para apresentar termos e definições em um formato organizado e fácil de ler, como em um glossário ou dicionário real, onde você pode encontrar palavras com suas definições correspondentes.

Este é um exemplo de uma lista de descrição em HTML com dois termos e seus detalhes correspondentes:
```html
<dl>
  <dt>HTML</dt>
  <dd>HyperText Markup Language</dd>
  <dt>CSS</dt>
  <dd>Cascading Style Sheets</dd>
</dl>
```

Neste caso, os termos são as siglas HTML e CSS, e os detalhes são suas expansões. Os detalhes também podem ser definições ou outras informações relacionadas aos termos.

Você precisará de três elementos HTML para definir uma lista de descrição. Primeiro, o elemento da lista de descrição, **dl**, que é o contêiner para a lista inteira. Você pode vê-lo envolvendo todos os outros elementos da lista de descrição no exemplo.

Em seguida, um elemento de termo descritivo, dt, para cada termo. Neste caso, a lista de descrição tem dois termos, HTML e CSS, portanto, tem dois desses elementos.

E, por fim, após cada termo, você encontrará um elemento de detalhes descritivos, dd, para a descrição ou os detalhes associados a esse termo. Neste exemplo, eles são Linguagem de Marcação de Hipertexto e Folhas de Estilo em Cascata.

No navegador, você verá cada termo seguido pela descrição correspondente. Por padrão, as descrições são ligeiramente recuadas para a direita para diferenciá-las visualmente.

Mas as listas de descrição não se limitam apenas a termos e definições. Elas são muito mais versáteis do que isso. Aqui temos uma receita com dois ingredientes.

```html
<dl>
  <dt>Flour</dt>
  <dd>2 cups</dd>
  <dt>Sugar</dt>
  <dd>1/2 cup</dd>
</dl>
```
A lista de descrição completa está dentro de um elemento de lista de descrição. O primeiro ingrediente, **Flour**, está dentro de um elemento de termo de descrição. Então, você pode ver a quantidade desse ingrediente que precisará: **2 cups**. Ele está dentro de um elemento de detalhes de descrição, logo após os ingredientes correspondentes.

E a mesma estrutura se repete para **Sugar**. Neste caso, a receita tem apenas dois ingredientes, mas se houvesse mais, a mesma estrutura poderia ser repetida em toda a lista descritiva.

No navegador, você verá os ingredientes alinhados à esquerda e as medidas recuadas para separá-los visualmente.

Outros casos de uso para listas de descrição incluem especificações de produtos, perguntas frequentes, informações de contato e metadados. Essencialmente, quando você tem duas informações relacionadas em um formato de par chave-valor, onde uma atua como um rótulo, a chave, e a outra atua como informação relacionada adicional, o valor, você pode usar uma lista de descrição.