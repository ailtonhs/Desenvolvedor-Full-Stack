# Quais são os diferentes estados de link e por que eles são importantes?

Você já deve ter visto um link em uma página da web ficar roxo depois de clicar nele. Isso ocorre porque o estado do link mudou, então um estilo diferente é aplicado. Há cinco estados diferentes em que um link pode estar.

O primeiro é o estado padrão, que é **:link**. Este estado representa um link que o usuário ainda não visitou, clicou ou interagiu. Você pode pensar neste estado como o que fornece os estilos base para todos os links da sua página. Os outros estados são construídos sobre ele.

O segundo estado é **:visited**, que se aplica quando um usuário já visitou a página vinculada. Por padrão, isso deixa o link roxo, mas você pode usar CSS para fornecer uma indicação visual diferente ao usuário. Isso é útil para informar alguém que já leu parte da sua documentação. Ou que o site é confiável, pois já o utilizou antes.

O terceiro estado é **:hover**. Este estado se aplica quando um usuário passa o cursor sobre um link. Este estado é útil para dar mais atenção a um link, garantindo que o usuário realmente pretenda clicar nele.

Então temos **:focus**. Esse estado se aplica quando focamos em um link.

E, por fim, temos **:active**. Este estado se aplica a links que estão sendo ativados pelo usuário. Isso normalmente significa clicar no link com o botão esquerdo do mouse, na maioria dos casos. Este estado pode ser útil para mostrar ao usuário que o elemento em que ele clicou é interativo.

Ao usar esses estados para estilizar seus links, há uma ordem específica na qual você precisa escrever seu CSS: l**ink**, **visited**, **hover**, **focus**, então **active**.

Agora você deve saber como dar um toque pessoal aos links da sua página e, ao mesmo tempo, fornecer as informações importantes que o usuário precisa sobre o estado de cada link.






