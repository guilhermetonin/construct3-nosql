# Jogo de Sobrevivência com Firebase Realtime Database

**DominationZombie** é um jogo de sobrevivência desenvolvido na plataforma **Construct 3**. O objetivo do jogo é sobreviver aos zumbis que nascem e tentar pontuar o máximo possível. A integração com o **Firebase** foi implementada para salvar a pontuação feita pelo jogador.

## ⌨️ Teclas 

- Use as teclas de direção **"WASD"** ou as **setas** para mover.
- Atire com o botão esquerdo do mouse.
- Pressione "**Espaço**" para reiniciar o mapa.

## 🎮 Jogue agora

   - Acesse [Domination Zombie](https://www.construct.net/en/free-online-games/domzombie-74961/play) no seu navegador ou aplicativo.
     
## 📜 Aplicação

   - No Construct 3, foram usadas essas ações para implementar o Firebase Realtime Database dentro do jogo.

![NoConstruct3](https://github.com/guilhermetonin/construct3-nosql/blob/08b9d4e67a9228523a954be422e15a91206d735b/images/implementacao.png)

   - Ao morrer no jogo, aparece a tela de morte, com a **lista de jogadores** e suas **pontuações**, além de uma aba para **inserir seu nome**, caso queira aparecer também. Há um **botão de envio**, que envia as informações relativas ao nome digitado e à pontuação obtida no jogo para o **banco de dados**.

![NoJogo](https://github.com/guilhermetonin/construct3-nosql/blob/c106629a63d0152ef7637d0729f7b08bb812b25a/images/implementacao3.png)

   - Dentro do **banco de dados Firebase**, é possível ver o **nome** e a **pontuação dos jogadores**, que são atualizados automaticamente ao clicar no botão **"Enviar"**.

![Firebase](https://github.com/guilhermetonin/construct3-nosql/blob/c106629a63d0152ef7637d0729f7b08bb812b25a/images/implementacao4.png)


Consiste em enfrentar hordas de zumbis, tentando sobreviver o maior tempo possível. Possui diversos recursos como:

- **Sistema de Arma**: Atire nos zumbis para matar-los
- **Dificuldade**: A cada 60 segundos os nascem mais rápido.
- **Ranking de pontuação**: A pontuação é salva no Firebase, permitindo que o jogador visualize seu desempenho em relação a outros.

### Funcionalidades

- **Animações e Sons**: Contém animações de dano, de tiro e sons, como o de acertos e elimnações e música de fundo.
- **Registro de Pontuação**: A pontuação do jogador é salva no Firebase após cada partida.
- **Scoreboard**: O Firebase armazena as pontuações, permitindo que o jogador veja seu desempenho comparado aos outros.








## 🎨 Créditos

- **Sprites** de zumbis, personagens e objetos foram criados por **"Kenney.nl"** ou **"www.kenney.nl"**.
- **Música de fundo** foi criada por **Zach Beever** e **Armin Hass**, estão dentro do jogo "Project Zomboid".
- **Fonte**: Endless Scarry, criada por **Akhmad riyan danuarta**.

Este projeto é de **uso acadêmico** e não tem fins comerciais. Todos os direitos dos recursos utilizados pertencem aos respectivos autores.

