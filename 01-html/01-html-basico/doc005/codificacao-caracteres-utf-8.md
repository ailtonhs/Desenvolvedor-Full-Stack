# O que é codificação de caracteres UTF-8 e por que ela é necessária?

**UTF-8**, ou **UCS Transformation Format 8**, é uma codificação de caracteres padronizada amplamente utilizada na web. A codificação de caracteres é o método que os computadores usam para armazenar caracteres como dados. Essencialmente, todo texto em uma página web é uma sequência de caracteres armazenada como um ou mais bytes. Na computação, um bite é uma unidade de dados composta por 8 bits, ou dígitos binários. O UTF-8 suporta todos os caracteres do conjunto de caracteres Unicode, incluindo caracteres e símbolos de todos os sistemas de escrita, idiomas e símbolos técnicos.

Aqui está um exemplo de uso do **meta** elemento com o **charsert** atributo para definir a codificação de caracteres como **UTF-8**:
```html
<meta charset="UTF-8">
```
Ao definir a codificação de caracteres como UTF-8, você garante que o **"e"** caractere acentuado (**é**) seja exibido corretamente na página.

Aqui está um exemplo de código estendido do uso da codificação de caracteres UTF-8:

```html
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Examples of the UTF-8 encoding</title>
    </head>
    <body>
        <p>Café</p>
    </body>
</html>
```
Para cada novos projetos criado, você deve incluir este **meta** elemento com o **charset** atributo definido como **UTF-8**.