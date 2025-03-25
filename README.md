![DOM. ZOMBIE](https://github.com/guilhermetonin/construct3-nosql/blob/53f2c16655a0b6acbfb8a6d1fca2dde0be869129/images/logogame.png)


É um jogo de sobrevivência desenvolvido na plataforma **Construct 3**. O objetivo do jogo é sobreviver aos zumbis que nascem e tentar pontuar o máximo possível. A integração com a **Firebase Realtime Database** foi implementada para salvar a pontuação feita pelo jogador.

## Comandos: 

- Use as teclas de direção "**WASD"**" ou as "**SETAS**" para mover.
- Atire com o "**BOTÃO ESQUERDO**" do mouse.
- Pressione "**ESPAÇO**" para reiniciar o mapa.

## Jogue agora:

   - Acesse [DominationZombie](https://www.construct.net/en/free-online-games/domzombie-74961/play) no seu navegador.
     
## Aplicação:

   - No Construct 3, foram usadas essas ações para implementar o Firebase Realtime Database dentro do jogo.

![NoConstruct3](https://github.com/guilhermetonin/construct3-nosql/blob/08b9d4e67a9228523a954be422e15a91206d735b/images/implementacao.png)

   - Ao morrer no jogo, aparece a tela de morte, com a **lista de jogadores** e suas **pontuações**, além de uma aba para **inserir seu nome**, caso queira aparecer também. Há um **botão de envio**, que envia as informações relativas ao nome digitado e à pontuação obtida no jogo para o **banco de dados**. Para **ver** seu nome e pontuação é necessário **reiniciar** a fase.

![NoJogo](https://github.com/guilhermetonin/construct3-nosql/blob/c106629a63d0152ef7637d0729f7b08bb812b25a/images/implementacao3.png)

   - Dentro do **banco de dados Firebase**, é possível ver o **nome** e a **pontuação dos jogadores**, que são atualizados automaticamente ao clicar no botão **"Enviar"**. <br><br>

![Firebase](https://github.com/guilhermetonin/construct3-nosql/blob/c106629a63d0152ef7637d0729f7b08bb812b25a/images/implementacao4.png)

   - Vídeo de exemplificação abaixo.<br><br>
     

https://github.com/user-attachments/assets/8fe38f60-4778-456e-b40b-009cced3b3cf



## Recursos:

Consiste em enfrentar hordas de zumbis, tentando sobreviver o maior tempo possível.

- **Sistema de Arma**: é preciso atirar nos zumbis para matar-los
- **Dificuldade**: a cada 60 segundos os nascem mais rápido e aumentam em um (1) sua vida.
- **Pontuação**: mate zumbis para aumentar sua pontuação
- **Animações e sons**: contém animações de dano, de tiro e sons de feedback, como o de acertos e eliminações e há uma trilha sonora de fundo.
- **Scoreboard**: o Firebase armazena as pontuações, permitindo que o jogador veja seu desempenho comparado aos outros.


________________________________________________________________________________________________________________________

###  Créditos

- **Sprites** de zumbis, personagens e objetos foram criados por "**Kenney.nl**" ou "**www.kenney.nl**".
- **Música de fundo** foi criada por "**Zach Beever**" e "**Armin Hass**" e está dentro do jogo "**Project Zomboid**".
- **Fonte**: Endless Scarry, criada por "**Akhmad riyan danuarta**".
- Este jogo é **inspirado** por um vídeo do YouTube. O conteúdo original **serviu de base** para a criação deste projeto.

   Vídeo original: ["Zombie shooter in construct 3"](https://youtu.be/P7cQN3OQD4c)

   Canal do YouTube: ["Game Design with Reilly"](https://www.youtube.com/@gamedesignwithreilly)

________________________________________________________________________________________________________________________
Este projeto é de **uso acadêmico** e **não tem fins comerciais**. Todos os direitos dos recursos utilizados **pertencem** aos respectivos autores.

