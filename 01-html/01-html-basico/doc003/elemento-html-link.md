# Qual é a função do elemento Link em HTML e como ele pode ser usado para criar links para folhas de estilo externas?

Vamos aprender sobre o **link** elemento e como usá-lo para vincular a folhas de estilo externas.

O **link** elemento é usado para vincular recursos externos, como folhas de estilo externas.

O **link** elemento é usado para vincular recursos externos, como folhas de estilo e ícones de sites. 

Esta é a sintaxe básica para usar o **link** elemento em um arquivo CSS externo:
```html
<link rel="stylesheet" href="./styles.css">
```
O **rel** atributo é usado para especificar a relação entre o recurso vinculado e o documento HTML. Nessa situação, precisamos especificar que esse recurso vinculado é um **stylesheet**.

Considera-se prática recomendada separar HTML e CSS em arquivos diferentes. Os desenvolvedores usarão o **link** elemento para seus arquivos CSS externos em vez de escrever tudo no documento HTML.

O **href** atributo é usado para especificar o local da URL para o recurso externo.

O **ponto** seguido por uma barra no exemplo informa ao computador para procurar o **styles.css** arquivo na pasta ou diretório atual.

O **link** elemento deve ser colocado dentro dentro do **head** elemento, como visto no exemplo a seguir:
```html
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Examples of the link elemento</title>
<link rel="stylesheet" href="./styles.css">
</head>
```

Muitas vezes, você verá vários **link** elementos dentro de uma base de código profissional que se vinculam a diferentes folhas de estilo, fontes e ícones.

Aqui está um exemplo de uso do **link** elemento para vincular a uma fonte externa do Google chamada **playwright Cuba**:
```html
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Playwrite+CU:wght@100..400&display=swap" rel="stylesheet">
```
o Google Fonts é um conjuto de fontes personalizadas, gratuitas e de código aberto que você pode usar em qualquer projeto. Você pode escolher quais fontes deseja usar e o Google fornecerá o código HTML e CSS necessário. Neste exemplo, o **preconnect** valor do **rel** atributo informa ao navegador para criar uma conexão antecipada com o valor especificado no **href** atributo. Isso é feito para acelerar o tempo de carregamento desses recursos exernos.

Outro uso comum do **link** elemento é a vinculação a ícones. Aqui está um exemplo de vinculação a um favicon:
```html
<link rel="icon" href="favicon.ico">
```
Um favicon, abreviação de ícone favorito, é um pequeno ícone normalmente exibido na aba do navegador, ao lado do título do site. Muitos sites usam favicon para exibir o ícone da sua marca.

