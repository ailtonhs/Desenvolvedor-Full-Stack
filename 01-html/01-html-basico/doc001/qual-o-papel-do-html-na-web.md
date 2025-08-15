# Qual o Papel do HTML na Web?

**HTML**, sigla para **Hypertext Markup Language**, é uma linguagem de marcação para a criação de páginas web. 

Quando você visita um site e vê conteúdo como parágrafos, títulos, links, imagens e vídeos, isso é **HTML**. **HTML** representa o conteúdo e a estrutura de uma página web por meio do uso de elementos.

Veja um exemplo de um elemento de parágrafo:

```html
<p>Hello</p>
```
A maioria dos elementos terá uma tag de abertura e uma tag de fechamento. Às vezes, essas tags são chamada de tags de início e fim. Entre essas duas tags, você encontrará o conteúdo. Esse conteúdo pode ser texto ou outros elementos HTML.

Tanto a tag de abertura quanto a de fechamento começam com um colchete angular esquerdo **(&lt;)** e terminam com um colchete angular direito **(&gt;)**, com o nome da tag posicionado entre esses colchetes angulares.

Aqui está uma análise mais detalhada das tags de parágrafo de abertura e fechamento:
```html
<p>
</p>
```

O que distingue uma tag de abertura de uma tag de fechamento é a barra **(/)** colocada imediatamente após o sinal de menor que o ângulo esquerdo em uma tag de fechamento.

Alguns elementos HTML não possuem uma tag de fechamento. Eles são conhecidos como elementos nulos.

Aqui está um exemplo de um elemento de imagem que é um elemento nulo:
```html
<img>
```
Observe que este elemento de imagem não possui a tag de fechamento e não possui nenhum conteúdo. Elementos vazios não podem ter nenhum conteúdo e possuem apenas uma tag inicial.

Às vezes, você verá elementos void que usam a **/** antes de, **&gt;** como este:
```html
<img/>
```

Embora muitos formatadores de código, como **Prettier**, optem por incluir os **/** elementos in void, a especificação HTML afirma que a presença do **/** "não marca a tag inicial como autofechamento, mas é desnecessária e não tem efeito algum".

No desenvolvimento do mundo real, você verá ambas as formas, por isso é importante estar familiarizado com ambas.

Se você quiser exibir uma imagem, precisará incluir alguns atributos dentro do seu elemento de imagem. Um atributo é um valor especial usado para ajustar o comportamento de um elemento HTML.

Aqui está um exemplo de um elemento de imagem com um **src** atributo, ou source:
```html
<img src="image-location"/>
```

O **src** atributo é usado para especificar a localização da imagem. Para elementos de imagem, é recomendável incluir outro atributo chamado **alt** atributo.

Veja um exemplo de um elemento de imagem com os atributos **src** e **alt**:
```html
<img src="example-cat-img-url" alt="Cat sleeping in the grass">
```

O **alt** atributo é usado para fornecer um texto curto e descritivo para as imagens.


Então, você deve estar se perguntando se o HTML por si só é suficiente para criar um site. Bem, a resposta é: depende. Se você estiver criando um pequeno projeto prático que exibe apenas texto e imagens, o HTML por si só pode ser suficiente. No entanto, se estiver criando um site profissional moderno, precisará de HTML, CSS e JavaScript.

HTML é para o conteúdo e a estrutura. CSS é para o estilo. JavaScript é para adicionar interatividade às suas páginas web. Uma boa analogia para isso é comparar HTML, CSS e JavaScript com um edificio completo. HTML representa os blocos, concreto e ferros que compõem as paredes. É a fundação que torna o edifício forte. CSS representa o design interno e externo que torna a casa bonita. JavaScript representa o sistema elétrico e hidráulico que garante acesso ininterrupto à água e à eletricidade.
