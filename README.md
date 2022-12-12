<html>
  <body>
    <h1> MUSIC PLAYER</h1>
Este repositório contém o projeto de um tocador de música desenvolvido para a disciplina "Fundamentos da Programação II".<br> 
Técnico Integrado em Informática. <br>Turma: P3 - 2022.2.<br>
<div style="display: inline_block"><br>

<h1> QUESTÕES</h1>

1) Substituir a imagem do fone de ouvido por uma outra de seu gosto. Crie sua própria, se você souber (usando a tag svg, por exemplo) ou procure uma na internet. Neste caso, busque por "royalty free images", de preferência imagens vetoriais e com fundo transparente.

2) Modificar a cor de fundo do player para a cor de sua preferência

3) Modificar a fonte usada no player para a de sua preferência

4) Modificar as músicas com as suas preferidas. 

5) Exibir na lista de músicas o título apenas, sem a extensão do arquivo.

6) Explique, com suas próprias palavras, o que faz o seguinte trecho de código:

const createSongList = () => {
  const list = document.createElement("ol");
  for (let i = 0; i < songs.length; i++) {
    const item = document.createElement("li");
    item.appendChild(document.createTextNode(songs[i].slice(0,-4)));
    list.appendChild(item);
  }
  return list;
};

7) Modifique o código para quando você clicar sobre a barra de progresso, a música avançar para o ponto correspondente


 <img align="center" alt="Java" height="500" width="700" src="https://github.com/holandalarissa/MusicPlayer/blob/85f4dd8cf76a7b4e791fe9f8315ebff44d579e73/fun-javascript-projects.com-master/fun-javascript-projects.com-master/Music%20Player/Music/music.png">
