# nc-final-project
2D PvP Space Shooter

## Project Description:

An online game where 2 players are matched, and pilot their own space ships and fire at each other to drain health


## MVP
- Start Screen: Titles, name input, instructions, start button, waiting message
- Client can render webpage
- Client connects to websocket
- Client send and receive information via server
- Client can move/orient ship, and fire
- Clients are updated of the others coordinates, orientation, health etc.
- Client is informed of connection error
- Client receives a win/lose message, play again button

## Additional Features
-   Login/Signup abilty
-   Win/Loss stats
-   Abilty to customise appearance
-   Leaderboard
-   stream a soundtrack in background


##Spiking tasks:
-   https://trello.com/b/QfHkozPL/space-wars






2 player 2D space shooter game, where your ship follows mouse attempting to destroy other ship
         
        MVP: Input player name, server connects you to available player, game mechanics, real time, player wins message

        Tech Stack: Pixi.js (or Phaser),                   Socket.io/WebSocket, JS (mySQL for additional stuff)

        Additional:-Users and stats/scores stores in DB.
                
                - if 1 player, fighting against npcs that spawn faster and gravitate towards
                - appropriate player matching

        Alternative: 1 player vs simple enemies that spawn at faster rates as level increases.