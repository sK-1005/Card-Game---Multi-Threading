# Card-Game---Multi-Threading
Java. 1 Manager - 4 Players - 1 Table - deck of 52 Cards - Let's Play!!!!!!

Consider the SDHC card game. SDHC stands for Spade, Diamond, Heart and Clubs respectively. This game is played between game manager and players. Game manager distributes the card, sets the turn of players, and computes the round winner and game winner. Players throws the card in each round. 

It has following rules:

There are four players (P1, P2, P3, P4) playing with one deck of cards. (1 deck=52 cards) 

Cards are distributed equally among 4 players and each player gets 13. 

Each Player throws card based on policy that is described below. 

Player throws the card in circular fashion. Like first round start by Player P1 then P2, P3 and P4 throws card one after the other. 

Similarly second round starts with P2 followed by P3, P4 and P1 sequentially. This process is repeated for 13 rounds. 

After each round (when all players throw cards) round winner is computed by game manager based on the rankings of the cards that is mentioned below. The player who throws highest weighted card wins the respective round. 


After each round the table is emptied. 

• These steps are repeated 13 times till all the cards are exhausted. 

• The player who wins the maximum number of rounds will be declared as a game winner

 

Total weight of a card depends on the number and the category

It is computed as:

Total weight= weight of the category of the card + weight of the Number on the card. 

Rules of the Game 

• The player who starts the round, throws the maximum weighted card among available card with him. 

• Remaining players check the highest weighted card on the table, compares with his highest weighted card. If his card weight is higher than the highest weighted card on table than throws that card otherwise he throws least weighted card from his cards. 

• The player who wins the maximum rounds, is declared as a winner. 

• Assume, there will no tie between players. 

