Overview

 

Theme / Setting / Genre
- Arcade Scoring game
- Wooden House setting

Project Description 

Our group consists of two members, Christopher Lychealdo in charge of game mechanics and GUI) and Steven Muliamin (in charge of game mechanics, animation, and GUI). This is a game that we have created as a final project submission of COMP6025 – Computer Graphics course at Binus University International.
We came up with the idea of creating a game that is based on a popular real-life casual game. The game is called “Can Throw Championship”. In real life, this game is usually played at a night market. Basically, you need to throw a ball to a stack of cans, and your score is based on the total number of cans that you have successfully dropped from the table.
The game that we have created is a web-based game developed using the Babylon.js engine. We also used Cannon.js plugin as it is needed by Babylon.js as the physics engine.
To make the game more challenging, we decided not to put any helper, such as a crosshair, so that it is much more similar to the game in real life. We also added lives (3 balls to throw) to create avoid the game from ending so quickly, and also to give the chance to the players to learn the correct camera rotation and power needed to drop all 9 cans.

Core Gameplay Mechanics Brief
- Physics: The game uses Cannon.js physics plugin to simulate the gravity, impostor, and impulse (power of the shot).
- Trigonometry: The calculation of the impulse uses trigonometry to calculate the power of impulse on a particular rotation of the camera.
- Life: The player only has 3 balls for a session of game.
- Points: The player gains a point for every can that has been dropped off the table.
- Controls: The main controls of the game are:
	-	Spacebar to initiate a shot
	-	Left mouse button to gain control of camera and mouse movement to rotate camera.
	-	R to restart the game.
Targeted platforms
Web browser – This game is made to be played on internet browsers.
Project Scope 
- The project took about one and a half months to complete including the mechanics and user interface.
- Core team
	-	Christopher Lychealdo 1901498422 + christopher97 (github account) - In charge of GUI and game mechanics.
	-	Steven Muliamin 1901499280 + Steven-zz (github account) - In charge of GUI, animation, and game mechanics.
- Libraries used
	Babylon.js
	Cannon.js
	Hand.js
- Programs used during development
	PHPStorm
	Sublime Text 3
	Mozilla Firefox
Story and Gameplay

Story 

The story of them game is about a “can throw” (an imaginary sport) athlete, John Smith who is trying to prove to the audiences of the sport that he is better than his rival, Shawn Black. The result of the last 4 years has shown that both John and Smith are going neck and neck, but none of them has shown any superiority. In this game, you are playing as John Smith as he tries to score as many points as he can in a championship held at Woodbury city. You have to knock down as many cans as you possibly could in just 3 chances. Are you up to the challenge?

Gameplay 

The game starts with the animation of the door of the game arena being open, and you going inside the arena. As the door closes, the indicator bar under the remaining balls will become green, and you can start throwing your first ball. You get 1 point for every can that is dropped off the table. The indicator bar will become red and the game will then pause for 5 seconds before the indicator becomes green again which signals that you can throw your second ball. The same process will take place until the third ball has been thrown. The game will then end, and your final score will be shown. A message from your rival will also be shown at the end screen. You can then play the game again from the beginning after finishing a session.


Assets Needed

- 2D
	- Textures
		-	floor.jpg
		-	menu.jpg
		-	metal.jpg
		-	steel.jpg
		-	wall.png
- 3D
	- Environmental Art Lists
		-	Babylon.js box mesh (table, wall, and roof)
		-	Babylon.js ground mesh (ground)
		-	Babylon.js sphere mesh (ball)
		-	Babylon.js cylinder (can)	
- Sound
	- door_1.wav
