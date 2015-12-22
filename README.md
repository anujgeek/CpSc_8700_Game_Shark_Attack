# Game: Shark Attack
Created by: Anuj Agrawal (Email: anuja@clemson.edu)
<br>
Class website: http://people.cs.clemson.edu/~malloy/courses/8700-2015/index.html

Final project for:
<br>
Clemson University CpSc 8700 Object Oriented Software Development
<br>
Created using C++ and SDL

## Demo:

<a href="http://www.youtube.com/watch?feature=player_embedded&v=2exu1oP0Cw0" target="_blank"><img src="http://img.youtube.com/vi/2exu1oP0Cw0/0.jpg" alt="MARIO" border="10"/></a>

## Project description:

Shark Attack: Game and objective
The game is a horizontal scroller.
Objective of game is to kill or avoid all enemies (starfishes and angry yellow bird)
and reach the end to meet santa.
When you win the game, the game temporarily goes into GodMode
so that you can't get the player killed.
You can restart game at any point by pressing 'r' key. Restart will reset
GodMode, game conditions, the player and enemies.

Object Pool: Bullets
You can shoot (footballs) by pressing 'f' key.

Normal Enemy: Starfish
You can kill starfishes by shooting them with bullet.
You can avoid starfishes by jumping over them by pressing 'w' or 'Space' key.

AI Enemy: Angry Bird Yellow
These birds will come after you in a vertical direction when they are
within a certain distance from player (XML: enemySmart/minimumXDistanceToTriggerAttack)
but they won't change their horizontal path.
You can't kill these yellow birds, just avoid them.

Sounds:
Game will feature a background score and will also output sounds
at event points (jump, fire, player's death, enemy's death, restart, godmode, etc.)

Keys:

w a s d - For player movement

Use 'F1' key for help.
Use 'p' key to toggle pause.
Use 'o' key to toggle slow motion.
Use 'g' key to toggle god mode.
Use 'r' key to restart.

Sprites:
All backgrounds completely made from scratch in illustrator/photoshop.
Used vectors for characters from:
Shark, Angry Bird, Santa taken from: http://all-free-download.com/
Birds taken from: http://opengameart.org/content/game-characters-flying-birds-attack-sprite-sheets

Sounds taken from:
http://www.playonloop.com/
http://themushroomkingdom.net/
