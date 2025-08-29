# O que é um validador HTML e como ele pode ajudar a depurar seu código?

HTML é uma linguagem muito tolerante: os elementos ainda são renderizados mesmo quando você comete erros, como esquecer de incluir uma tag de fechamento.

Digamos que você tenha um **h2** elemento sem uma tag de fechamento:
```html
<h1>Article Topic</h1>
<h2>Subheading 1 </h2>
<h2>Subheading 2 </h2>

<!-- This h2 does not have a closing tag -->
<h2>Subheading 3
```
A **h2** tag sem fechamento ainda renderizará bem. Isso acontece porque os navegadores usam um algoritmo de análise que lida com erros comuns e tenta renderizar o HTML o mais próximo possível da intenção do autor.

Mas isso às vezes pode sair pela culatra. Vamos adicionar alguns parágrafos sob as tags de título 2 existentes no código:
```html
<h1>Article Topic</h1>
<p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Maiores, nisi.</p>

<h2>Subheading 1 </h2>
<p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. At, doloremque.</p>

<h2>Subheading 2 </h2>
<p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Unde, placeat.</p>

<!-- This h2 does not have a closing tag -->
<h2>Subheading 3
<p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Tempore, illum.</p>
```
Como resultado, o elemento de parágrafo sob a tag **h2** sem fechamento **h2** é renderizado como título 2. É por isso que você precisa de um validador HTML.

Um validador HTML é uma ferramenta que verifica a validade do seu código HTML em relação às especificações HTML padrão. Ele ajuda a identificar erros e avisos no seu código HTML, garantindo que suas páginas da web estejam estruturadas corretamente e em conformidade com os padrões da web.

Usar um validador HTML beneficia não apenas você e suas futuras revisões de código, mas também qualquer outra pessoa que analise seu código, como seus colegas de equipe e colaboradores de código aberto.

Existem vários validadores de HTML que você pode usar. O mais amplamente aceito é o **w3.org** serviço de validação de marcação.

