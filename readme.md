<h1>Desafio de projeto do Felipão: Mario Kart.JS</h1>

<table>
    <tr>
        <td>
            <img src="./docs/header.gif" alt="Mario Kart" width="200">
        </td>
        <td>
            <b>Objetivo:</b>
            <p>Mario Kart é uma série de jogos de corrida desenvolvida e publicada pela Nintendo. Nosso desafio será criar uma lógica de um jogo de vídeo game para simular corridas de Mario Kart, levando em consideração as regras e mecânicas abaixo.</p>
        </td>
    </tr>
</table>

<h2>Players</h2>
<table style="border-collapse: collapse; width: 800px; margin: 0 auto;">
    <tr>
        <td style="border: 1px solid black; text-align: center;">
            <p>Mario</p>
            <img src="./docs/mario.gif" alt="Mario Kart" width="60" height="60">
        </td>
        <td style="border: 1px solid black; text-align: center;">
            <p>Velocidade: 4</p>
            <p>Manobrabilidade: 3</p>
            <p>Poder: 3</p>
        </td>
        <td style="border: 1px solid black; text-align: center;">
            <p>Peach</p>
            <img src="./docs/peach.gif" alt="Mario Kart" width="60" height="60">
        </td>
        <td style="border: 1px solid black; text-align: center;">
            <p>Velocidade: 3</p>
            <p>Manobrabilidade: 4</p>
            <p>Poder: 2</p>
        </td>
        <td style="border: 1px solid black; text-align: center;">
            <p>Yoshi</p>
            <img src="./docs/yoshi.gif" alt="Mario Kart" width="60" height="60">
        </td>
        <td style="border: 1px solid black; text-align: center;">
            <p>Velocidade: 2</p>
            <p>Manobrabilidade: 4</p>
            <p>Poder: 3</p>
        </td>
    </tr>
    <tr>
        <td style="border: 1px solid black; text-align: center;">
            <p>Bowser</p>
            <img src="./docs/bowser.gif" alt="Mario Kart" width="60" height="60">
        </td>
        <td style="border: 1px solid black; text-align: center;">
            <p>Velocidade: 5</p>
            <p>Manobrabilidade: 2</p>
            <p>Poder: 5</p>
        </td>
        <td style="border: 1px solid black; text-align: center;">
            <p>Luigi</p>
            <img src="./docs/luigi.gif" alt="Mario Kart" width="60" height="60">
        </td>
        <td style="border: 1px solid black; text-align: center;">
            <p>Velocidade: 3</p>
            <p>Manobrabilidade: 4</p>
            <p>Poder: 4</p>
        </td>
        <td style="border: 1px solid black; text-align: center;">
            <p>Donkey Kong</p>
            <img src="./docs/dk.gif" alt="Mario Kart" width="60" height="60">
        </td>
        <td style="border: 1px solid black; text-align: center;">
            <p>Velocidade: 2</p>
            <p>Manobrabilidade: 2</p>
            <p>Poder: 5</p>
        </td>
    </tr>
</table>

<h3>🕹️ Regras & mecânicas:</h3>

<ul>
  <li>Dois personagens são escolhidos aleatoriamente para disputar a corrida.</li>
  <li>Os personagens irão correr em uma pista composta por 5 rodadas.</li>
  <li>Em cada rodada, será sorteado aleatoriamente um tipo de bloco da pista: <strong>RETA</strong>, <strong>CURVA</strong> ou <strong>CONFRONTO</strong>.</li>
  <li>
    Dependendo do tipo de bloco:
    <ul>
      <li><strong>RETA</strong>: cada personagem joga um dado de 6 lados e soma o resultado com seu atributo <strong>VELOCIDADE</strong>. Quem tiver o maior valor marca 1 ponto.</li>
      <li><strong>CURVA</strong>: cada personagem joga um dado de 6 lados e soma com seu atributo <strong>MANOBRABILIDADE</strong>. Quem tiver o maior valor marca 1 ponto.</li>
      <li><strong>CONFRONTO</strong>: cada personagem joga um dado de 6 lados e soma com seu atributo <strong>PODER</strong>. Quem tiver o menor valor perde 1 ponto, caso tenha pelo menos 1.</li>
    </ul>
  </li>
  <li>Nenhum personagem pode ficar com pontuação negativa (mínimo é 0).</li>
  <li>Ao final das 5 rodadas, o personagem com mais pontos vence a corrida.</li>
  <li>Em caso de empate, o resultado final será declarado como empate.</li>
</ul>
