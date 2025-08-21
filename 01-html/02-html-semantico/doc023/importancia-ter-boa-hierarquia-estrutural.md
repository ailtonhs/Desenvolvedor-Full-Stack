# Por que é importante ter uma boa hierarquia estrutural?

O aspecto mais importante da criação de uma hierarquia estrutural é o uso adequado dos elementos de título. Os elementos de título são numerados como **h1**, **h2**, **h3**, e assim por diante. Esses números representam o nível de título daquele elemento.

Assim como em um documento de texto, você não deve usar os níveis de título na ordem incorreta. Seu **h1** elemento é o título de nível superior. Raramente você terá mais de um desses em uma página, e ele normalmente deve vir antes de todo o seu conteúdo.

Seu **h2** elemento é o seu subtítulo. Ele deve sempre vir depois de **h1** e pode vir depois de algum texto introdutório. Ao contrário de um **h1** elemento, você pode ter vários **h2** elementos na sua página. Você costuma fazer isso para delinear diferentes seções de conteúdo.

Seguindo o padrão, seu **h3** elemento deve sempre vir depois de um **h2** elemento. Ou seja, você nunca deve pular diretamente de **h1** para h3. No entanto, você pode ter vários elementos de título no mesmo nível. Por exemplo, este código está correto:
```html
<div>
  <section>
    <h1>freeCodeCamp</h1>
    <h2>Learn Front-End Development</h2>
    <h2>Learn Back-End Development</h2>
  </section>
</div>
```

Mas esse código não estaria correto, pois **h3** vem antes de **h2**:
```html
<div>
  <section>
    <h1>freeCodeCamp</h1>
    <h3>Learn Front-End Development</h3>
    <h2>Learn Back-End Development</h2>
  </section>
</div>
```
Pode ser tentador usar um elemento de título específico devido ao seu estilo, como **h1** para textos grandes:
```html
<article>
  <p>
    Here is some
    <h1>Large Text</h1>
  </p>
</article>
```
Em vez disso, você deve escolher o elemento apropriado para a estrutura do seu documento e usar CSS para obter o estilo desejado.

Usar a hierarquia correta é importante para a acessibilidade. Tecnologias assistivas, como leitores de tela, dependem da estrutura de uma página web para determinar como analisá-la e anunciá-la ao usuário. Usar um **h3** elemento após um **h1** pode fazer com que o usuário de um leitor de tela acredite que pulou acidentalmente um conteúdo importante devido à ausência de um **h2** elemento.

Uma estrutura adequada também é importante para SEO. Os mecanismos de busca usam automação para analisar o conteúdo da sua página e determinar quando e onde ela deve aparecer nos resultados. Se a sua estrutura estiver malformada, os mecanismos de busca podem não conseguir ranqueá-lo muito bem nos resultados de pesquisa relevantes.

Por fim, dependendo de quão incorreta for a sua estrutura, o seu HTML pode nem ser tecnicamente válido. Quando isso acontece, o navegador precisa adivinhar o que você pretendia fazer. E o que ele adivinha pode nem ser o que você deseja.

Como você aprendeu hoje, há muitos motivos para usar a hierarquia estrutural adequada para sua página. Tenha isso em mente ao criar novos projetos.



