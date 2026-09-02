# Flappy-Bird-GameDev-Task
The Unity Tutorial For Complete Beginners by Game Maker's Toolkit

https://www.youtube.com/watch?v=XtQMytORBmM&t=1899s

My twist was to introduce a gravity flip mechanic which is enabled and disabled by the player themself.As an added incentive, when gravity is flipped the player gets 2 points for every pipe they pass. I also added sound effects and used a angry birds theme wherever I could (colour scheme, sounds, bird).

To create the gravity flip mechanic, I first created a boolean variable called "isGravityFlipped" in the script of the bird and set it to "false". Then I created a function "flip" flip is used to read the input "F" from the player and toggle the value of "isGravityFlipped". Subsequently; if it is true, the gravity scale attribute of the rigid body accessed  and inverted. Also the icon of the bird is flipped. Flip is called in update. Also in update an if/else conditional is set to recognise whether or not gravity is flipped and accordingly change the direction of velocity.

To make every pass worth 2 points, I accessed birdscript in triggerscript and used the variable isgravityfliped in an if/else conditional to change the argument of the score function accordingly.

I struggled during the challenge of the first unit of the unity lessons with the rotation of the plane and the axis and stuff which was originally in the files so I switched to using input action and set it up in Vector2.

Also, initially I wanted to create a randomised gravity flip mechanic but i could not quite figure it out so I switched to making it the player's choice and adding an incentive. 

I did end up using AI a few times to debug my scripts and also to help me flip the sprite.

With more time I'd add an initial scene which allows the player to select what bird they want to play with and give each bird its own attributed like in the angry bird games.

I was extremely short on time because I was with my family on holiday during the long weekend so couldn't complete unit 2 of the unity tutorials and instead just started with the youtube tutorial of the game. I'm sorry.
