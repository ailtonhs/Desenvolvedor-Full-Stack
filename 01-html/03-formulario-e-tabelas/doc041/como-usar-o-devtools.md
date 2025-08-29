# Como usar o DOM Inspector e o DevTools para depurar e construir seus projetos

Ao desenvolver seus projetos, você frequentemente encontrará problemas em que seus programas não funcionam como esperado.

Os programadores costumam se referir a problemas como bugs. O processo de encontrar e corrigir esses bugs é conhecido como depuração.

Para depurar seu código, você precisará usar algumas ferramentas fornecidas pelo seu navegador.

Duas ferramentas importantes a serem usadas seriam o inspetor DOM e as ferramentas do desenvolvedor.

O inspetor DOM permite que você inspecione a estrutura HTML da página em que você está.

DOM significa Document Object Model (Modelo de Objeto de Documento). É uma estrutura em forma de árvore que representa os elementos de uma página. Você aprenderá mais sobre o DOM em módulos posteriores.

As ferramentas do desenvolvedor permitem que você inspecione o HTML, CSS e JavaScript da página em que você está.

Vamos dar uma olhada em um exemplo de HTML que contém um pequeno bug no elemento âncora:
```html
<a href="https://www.freecodecamp.org/larn/">freeCodeCamp curriculum</a>
```
Ao clicar no link, você será direcionado para uma página 404. Uma página 404 é uma página de erro que aparece quando um usuário tenta acessar uma página da web que não existe no servidor.

A intenção é que o link leve ao currículo do freeCodeCamp.

Para ver qual pode ser o problema, você pode usar as ferramentas do desenvolvedor.

Para abrir as ferramentas do desenvolvedor no seu navegador, você pode clicar com o botão direito na página e selecionar **Inspect**.

Você também pode usar **Control Shift I** no teclado do seu PC ou **Command Option I** no seu Mac.

Ao abrir as ferramentas do desenvolvedor no Google Chrome, você verá várias abas. A primeira aba é chamada de **Elements** aba. Esta aba mostra a estrutura HTML da página em que você está.

A segunda aba é chamada de **Console** guia. Ela mostra quaisquer erros que possam estar ocorrendo na página.

Caso haja um link quebrado, você pode verificar o console para ver as mensagens de erro referentes a esse link quebrado. A mensagem comum que continua sendo exibida para links quebrados é o erro 404. O erro 404 indica que a página não foi encontrada.

Isso nos permite saber que o problema está na URL do elemento âncora. Ao inspecionar o **href** valor, você verá que há um erro de digitação.

No momento, a mensagem do console mostra **/larn** um erro 404, mas o URL correto deveria ser **/learn**. Quando o link for corrigido, funcionará como esperado.

