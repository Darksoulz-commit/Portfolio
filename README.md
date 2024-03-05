# Swiggy coding assessment

The given text presents a simple game that is text-based and has been implemented in Java. The game imitates combat involving 2 players with health, strength and attack attributes.

## Classes

### Player Class

The player class denotes one of the participants within the game. Every player has:

- Health: which shows life points of the player.

- Strength: this is used to repel against an attack.

- Attack: this is used for assaulting other players.

Furthermore, the Player class has these methods:

- rollDice() – it simulates a dice roll and returns a random number from 1 to 6;

- attack player(Player defender) – it determines how much damage will be inflicted on 
the attacked player based on attack value of attacker and dice rolling; moreover, this 
damage will be subtracted from defenders’ health.

### Main Class

This `Main` class possesses `main` method by which program starts running. It creates two `Player` objects and simulates battling between them when one eventually loses all the health below zero.

## How to Play

As soon as you run the program, you need to input values for various attributes such as `health`, ‘strength’, and ‘attack’ belonging to every participant of the gaming process. From there forth, the game runs through a loop where each time it’s one player at a time attacking another until one players’ health level falls into or below zero meaning somebody else emerges as victorious
