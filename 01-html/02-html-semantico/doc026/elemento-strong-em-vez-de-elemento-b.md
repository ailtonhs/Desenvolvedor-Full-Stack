# Quando você deve usar o elemento forte em vez do elemento que chama a atenção?

O elemento "chamar atenção para", **b**, é comumente usado para destacar palavras-chave em resumos ou nomes de produtos em avaliações. Normalmente, os navegadores exibem esse texto em negrito. Veja um exemplo usando o **b** elemento para destacar nomes de produtos nesta avaliação:
```html
<p>
  We tested several products, including the <b>SuperSound 3000</b> for audio
  quality, the <b>QuickCharge Pro</b> for fast charging, and the
  <b>EcoClean Vacuum</b> for cleaning. The first two performed well, but the
  <b>EcoClean Vacuum</b> did not meet expectations.
</p>
```
O navegador renderiza essas partes do texto em negrito. Essa ênfase visual chamará a atenção dos leitores para os nomes dos produtos.

Se você precisar enfatizar a importância do texto, use o **strong** elemento em vez do **b** elemento.

**strong** é um elemento HTML semântico que enfatiza textos cruciais ou urgentes. Este é um exemplo em que o **strong** elemento é usado para rotular um aviso muito importante sobre as potenciais reações alérgicas que os clientes podem ter a um produto:
```html
<p>
  <strong>Warning:</strong> This product may cause allergic reactions.
</p>
```
O **strong** elemento comunica essa sensação de urgência.

Visualmente, ambos são muito semelhantes, pois são renderizados em negrito por padrão. Mas seus significados são bem diferentes. Enquanto o elemento "trazer atenção para" apenas chama a atenção para o texto, sem indicar o nível mais alto de importância, o **strong** elemento faz mais do que isso. Ele transmite uma sensação de importância ou urgência. Essa é a principal diferença.

Para escolher entre eles, considere o propósito do texto e sua importância dentro do conteúdo ao redor.

