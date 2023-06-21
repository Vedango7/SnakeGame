# SnakeGame
LCOME TO PROJECT "SNAKE GAME" THIS IS MY FIRST PROJECT USING JAVA LANGUAGE

-> INTRO <-

This game is all about controlling the snake using key buttons, making it eat food, increasing the snake's size and scores, and ending the game when the snake collides with obstacles.
SNAKE GAME INCLUDES THREE DOTS which is
RED DOT -> HEAD OF THE SNAKE. GREEN DOT's -> BODY OF THE SNAKE. APPLE PICTURED GREEN DOT -> FOOD FOR THE SNAKE.

-> FUNCTIONALTIES <-

BASIC UI // which includes the frames, content, content pane, dimensions, and color of the background.
GRAPHICS // which involves loading images and drawing components on the right position.
LOCATING THE APPLE // which includes randomizing the Apple's position
CONTROLLOING // which includes controlling the snake using arrow keys and checking for collisions with the border and the body.
MECHANICS & DYNAMICS // which covers its movement and how it eats food.
CONCLUDING // which covers displaying the score and game over message when the game ends.
-> DETAILED IMPLEMENTATION OF FUNCTIONALTIES <-

*BASIC UI

The components of the game are the board, the snake, and the app, each with their own properties that need to be initialized.
The board is a rectangular box with a height and width that contains the game.
The snake is a bunch of dots with a size and dot size, and the apple is a single size called torque size.
The maximum number of dots that can fit in the board is calculated as 400/10 multiplied by 400/10, which equals 1600.
The positions of the snake are defined by two arrays for the X and Y coordinates on the Java Swing application.
*GRAPHICS

First we need to prepare resources and draw images at specified positions.
Create new folder called resources inside src folder.
Mark Resources folder as a resources folder.
Download provided images from GitHub repository and save in Resources folder(IF YOU NEED).
Load images inside Image class by creating Image objects for each image needed (body, head, apple).
*LOCATING THE APPLE

Intially the position of the apple is fixed.
As the game progress we need to randomize the apple's position each and everytime.
To achieve this, the position of the apple will be randomized every time the application restarts using MATH CLASS.
Apple size is 10.
Values for the apple's position should be a multiple of 10.
Using IN-Built JAVA FUNCTION MATH.RANDOM we can achieve this.
*CONTROLLING THE SNAKE

First step is to implement controls using a Key Adapter Class.
Key Adapter Class will be customized by extending its properties and overriding its key pressed method.
Key events will be generated whenever arrow keys or other keys are clicked.
The key code for the clicked key will be obtained using get key code.
The direction of the snake will be determined based on the clicked key.
If the snake is already moving in a certain direction, clicking the opposite direction will be considered an INVALID MOVE.
The snake's direction will be updated accordingly based on the clicked key and the current direction of the snake.
All other directions will be set to false when a certain direction is true.
*MECHANICS & DYNAMICS OF THE GAME

The snake's movement is dependent on a timer class that triggers a move operation.
There are FOUR POSSIBLE DIRECTIONS for the snake to move: RIGHT, LEFT, UP, DOWN.
The coordinates of the snake's body are determined by its dot size and its initial position.
When the snake moves in a particular direction, only the head's X-coordinate changes, while the other dots follow their previous position.
The X-coordinate of each dot in the snake's body decrements by its slot size if it is moving in the left direction and increments if it is moving in the right direction.
The Y-coordinate of each dot in the snake's body decrements if it is moving in the upward direction and increments if it is moving in the downward direction.
The head's position is determined by subtracting the dot size from its X-coordinate if it is moving in the left direction.
The position of each subsequent dot in the snake's body is determined by subtracting 1 from its X-coordinate if it is moving in the left direction.
*CONCLUDING THE GAME

When the game ends we need to display "Game Over" message and SCORE of the game.
Game over message should be displayed in the center of the screen.
Score should be displayed below the game over message.
The HEIGHT OF THE SCREEN SHOULD BE DIVIDED INTO FOUR PARTS.
"GAME OVER" message should be displayed at H/4 and SCORE should be displayed at 3H/4.
X coordinate for the game over message should depend on the width of the message.
Point size of 14 can be used for height.
We need a Graphics object to draw a STRING.
Calculate the score by subtracting 3 from the number of dots and multiplying it by 100.
Use the INTEGER CLASS to CONVERT THE SCORE to a STRING.
Create a small point with bold font and size of 14.
Get the font metrics of the small point.
-> TECHNOLOGIES USED <-

*PROGRAMMING LANGAUAGE USED TO DEVELOP THE SNAKE GAME

USED JAVA AND JAVA ALONE.
AND USED JAVASCRIPT LIBRARY WHILE USING JAVA SWING.
*PLATFORM USED TO DEVELOP THE SNAKE GAME

The only technology used for making the Snake game is JAVA SWING LIBRARY, which provides lightweight components for making WINDOW BASED APPLICATIONS.
*CLASSES USED TO DEVELOP THE SNAKE GAME

Classes used in the game include's J Button, J check boxes, combo box, J File Chooser, and J Frame.
*STYLING OF THE SNAKE GAME

The styling of the project includes a window with a container for the game.
-> IMAGES FROM THE DEVELOPED SNAKE GAME <-

Screenshot_20230621-202923 Screenshot_20230621-203021 Screenshot_20230621-203059
