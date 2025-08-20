# Qual é a diferença entra barras um único ponto e um ponto duplo na sintaxe de caminho?

Você já deve ter visto links como **/public/logo.png, ./script.js, ou ../styles.css**. Mas o que esses tipos especiais de links significam? Eles são chamados de caminhos de arquivo. Há três sintaxes principais que você precisa conhecer. A primeira é a barra, que pode ser uma barra invertida **(\ )** ou uma barra normal **(/)**, dependendo do seu sistema operacional. A segunda é o ponto simples **(.)**. E, por fim, temos o ponto duplo (**..**).


A barra é conhecida como "separador de caminho". Ela é usada para indicar uma quebra no texto entre nomes de pastas ou arquivos. É assim que seu computador sabe que **naomis-files/** aponta para um diretório com o mesmo nome, enquanto **naomis/files/** aponta para um **files** diretório dentro do **naomis** diretório.

Um único ponto aponta para o diretório atual e dois pontos apontam para o diretório pai. Normalmente, você verá um único ponto usado para garantir que o caminho seja reconhecido como relativo. Lembre-se de que você aprendeu em uma aula anterior sobre caminhos relativos versus absolutos.

No entanto, pontos duplos são muito mais comuns para acessar arquivos fora do diretório de trabalho atual.

Por exemplo, dada está árvore de arquivos:

```
my-app/
├─ public/
│  ├─ favicon.ico
│  ├─ index.html
├─ src/
│  ├─ index.css
│  ├─ index.js
```

Se o seu **public/index.html** arquivo precisasse ser carregado **favicon.ico**, você usaria um caminho relativo com um único ponto para acessar o diretório atual: **./favicon.ico**. Se o seu **public/index.html** arquivo precisasse ser carregado **index.css**, você usaria um caminho relativo com dois pontos para navegar **my-app** primeiro até o diretório pai, depois até o **src** diretório e, finalmente, até o seu arquivo: **../src/index.css**.