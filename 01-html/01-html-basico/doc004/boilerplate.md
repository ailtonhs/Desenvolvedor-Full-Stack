# O que é um HTML Boilerplate e por que ele é importante?

Vamos aprender sobre o boilerplate HTML.

O que é o boilerplate HTML, você pergunta? É como um modelo pronto para suas páginas web. Pense nele como a base de uma casa. Um boilerplate inclui a estrutura básica e os elementos essencias que todo documento HTML precisa. Ele economiza seu tempo e ajuda a garantir que suas páginas estejam configuradas corretamente. 

Aqui está um exemplo:
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>freeCodeCamp</title>
    <link rel="stylesheet" href="./styles.css">
</head>
<body>
</body>
</html>
```

Vamos analizar as partes principais deste texto padrão. Primeiro, temos a **DOCTYPE** declaração:
```html
<!DOCTYPE html>
```
Ela informa aos navegadores qual versão do HTML você está usando. Em seguida, vem a tag **html**:

```html
<!DOCTYPE html>
<html lang="en">
    <!--Todos os outros elementos vão aqui dentro -->
</html>
```
Isso abrange todo o seu conteúdo e pode especificar o idioma da sua página. Dentro da tag **html**, você encontrará duas seções principais: a **head** e a **body**:

```html
<!DOCTYPE html>
<html lang="en">
    <head>
        <!--Metadados importantes vão aqui-->
    </head>
    <body>
        <!--Títulos, parágrafos, imagens, etc. vão aqui dentro-->
    </body>
</html>
```

A seção **head** contém informações importantes dos bastidores:
```html
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document Title Goes Here</title>
    <link rel="stylesheet" href="./styles.css">
</head>
```
Os metadados do seu site, contidos em **meta** elementos, contêm detalhes sobre aspectos como codificação de caracteres e como sites como o Twitter devem visualizar o link da sua página. O título do seu site, encontrado no **title** elemento, determina o texto que aparece na aba ou janela do navegador. Por fim, você normalmente vinculará as folhas de estilo externas da sua página na seção **head** usando **link** elementos.

A seção **body** é onde todo o seu conteúdo vai:
```html
<body>
    <h1>I am a main title</h1>
    <p>Example paragraph text</p>
</body>
```

Agora, por que um boilerplate é importante? ele garante que suas páginas sejam estruturadas corretamente e funcionem bem em diferentes navegadores. Usar um boilerplate ajuda a eviar erros comuns e a seguir as melhores práticas. É um ótimo ponto de partida para qualquer projeto web.

Lembre-se: você pode personalizar seu próprio boilerplate para atender às suas necessidades. À medida que você ganha experiência, pode adicionar seus próprios elementos ou **meta** tags preferidos. À medida que você aprimora seu boilerplate pessoal, você perceberá que ele economiza tempo ao iniciar novos projetos.