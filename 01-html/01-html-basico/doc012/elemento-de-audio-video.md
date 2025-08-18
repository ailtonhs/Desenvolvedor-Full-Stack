# Quais são as funções dos elementos de áudio e vídeo do HTML e como eles funcionam?

Os elementos **audio** e **video** permitem adicionar conteúdo de som e vídeo aos seus documentos HTML. O **audio** elemento suporta formatos de áudio populares como mp3, wav e ogg. O **video** elemento suporta os formatos mp4, ogg e webm.

Para incluir conteúdo de áudio em sua página da web, você pode usar o **audio** elemento com o **src** atributo apontando para o local do seu arquivo de áudio:

```html
<audio src="CrystalizeThatInnerChild.mp3"></audio>
```
Se você tentar executar este exemplo, verá que nada aparece na página. No entanto, se você inspecionar a página com as ferramentas do desenvolvedor, verá que o **audio** elemento está de fato na página. Se quiser ver o player de áudio na página, adicione o **audio** elemento com o **controls** atributo:
```html
<audio src="CrystalizeThatInnerChild.mp3" controls></audio>
```
O **controls** atributo permite que os usuários gerenciem a reprodução de áudio, incluindo ajuste de volume e pausa ou retomada da reprodução. O **controls** atributo é um atributo booleano que pode ser adicionado a um elemento para habilitar controles de reprodução integrados. Se omitido, nenhum controle será exibido.

Além dos atributos **src** e **controls**, existem vários outros atributos que aprimoram a funcionalidade do **audio** elemento. O **loop** atributo é um atributo booleano que faz com que o áudio seja reproduzido continuamente.

Aqui está um exemplo de uso do **loop** atributo para reproduzir uma das músicas de Quincy larson, intitulada "Can't stay down":

```html
<audio
  src="https://cdn.freecodecamp.org/curriculum/js-music-player/can't-stay-down.mp3"
  loop
  controls
></audio>
```
Quando a música chegar ao final, ela retornará ao loop e a reproduzirá novamente desde o início. Outro atributo que você pode usar é o **muted** atributo. Quando presente no **audio** elemento, este atributo booleano iniciará o áudio em um estado silenciado.

Veja um exemplo de uso do **muted**atributo:
```html
<audio
  src="https://cdn.freecodecamp.org/curriculum/js-music-player/can't-stay-down.mp3"
  loop
  controls
  muted
></audio>
```
Ao iniciar a música no navegador, você não ouvirá nada. Para ouvi-la, clique no ícone de volume.

Quando se trata de tipos de arquivo de áudio, existem diferenças entre os navegadores que suportam cada tipo. Para acomodar isso, você pode usar **source** elementos dentro do **audio** elemento e o navegador selecionará a primeira fonte que entender. 
Veja um exemplo do uso de vários **source** elementos para um **audio** elemento:

```html
<audio controls>
    <source src="audio.ogg" type="audio/ogg"/>
    <source src="audio.wav" type="audio/wav"/>
    <source src="audio.mp3" type="audio/mpeg"/>
</audio>
```
O navegador começará primeiro com o tipo ogg e, se não conseguir reproduzir o áudio, passará para o próximo tipo na lista.

Todos os atributos que aprendemos até agora também são suportados no **video** elemento. 
Aqui está um exemplo de uso de um **video** elemento com os atributos **loop**, **controls** e **muted**:
```html
<video
  src="https://archive.org/download/BigBuckBunny_124/Content/big_buck_bunny_720p_surround.mp4"
  loop
  controls
  muted
></video>
```
Para o **src** atributo, ou source, estamos usando um vídeo chamado "Big Buck Bunny" do archive.org. Se você quiser exibir uma imagem durente o download do vídeo, pode usar o **poster** atributo. Este atributo não está disponível para **audio** elementos e é exclusivo para cada **video** elemento.

Veja um exemplo de uso do **poster** atributo com conteúdo fornecido por peach.blender.org:

```html
<video
  src="https://archive.org/download/BigBuckBunny_124/Content/big_buck_bunny_720p_surround.mp4"
  loop
  controls
  muted
  poster="https://peach.blender.org/wp-content/uploads/title_anouncement.jpg?x11217"
  width="620"
></video>
```
Este exemplo também usa o **width** atributo para definir a largura para 620 pixels para que o vídeo caiba melhor na tela.
