================= Description =================
Avoid Obstacles game was developed for college purposes only. 

The game isn't done to perfection but its working
as it's should. At the beginning of the game user is presented with easy to understand messages, which provide
as how to start up the game and it's controls.

When the game has started player must avoid any red squares. If user hits one of the red square it automatically
results in losing one of the lifes which are present along with the score at the left top corner of the canvas.
When player is out of lifes game over sound gets played and game over screen is displayed with the score user got.

================= Requirements Meet =================
User interaction
	- Met by keyboard control of the player (green box)

Basic collision detection
	- Met by collision between the canvas boundaries (square and circle) and by collision between enemy and player

Cartesian to polar coordinates
	- Met by spliting circle into different segments

Transformation
	- Not fully met.
	- Haven't used any transformations, however enemies come in different size, speed and locations
	- Rotation is applied by rotating the circle at the first screen of the game

Multiple moving objects
	- Met by multiple enemy objects (red squares) moving
	- Also met by four circles moving and rotating around the first screen of the game

Sprites
	- Not sure if moving background is considered a sprite

Advanced
	- Not attempted.

Extra
	- Scoring system implemented
	- Scrolling background image
	- Audio for background music, losing life, and game over

================= Reference =================
Code was adapted from the following: 
	- http://atomicrobotdesign.com/blog/htmlcss/build-a-vertical-scrolling-shooter-game-with-html5-canvas-part-1/
	- Graphics Programming labs

