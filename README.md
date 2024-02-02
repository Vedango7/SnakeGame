* The Objective of the game are controlling the snake using key buttons, making it eat food, increasing the snake's size and scores, and ending the game when the snake collides with obstacles. The Game shows the snake game with a moving three-dot snake, a red dot for the head, green dots for the body, and an apple for the food. The only technology used for making the Snake game is Java Swing library, which provides lightweight components for making window-based applications. Classes that will be used in the game include J Button, J check boxes, combo box, J File Chooser, and J Frame.

* MECHANICS & DYNAMICS OF THE GAME

The snake's movement is dependent on a timer class that triggers a move operation.

There are FOUR POSSIBLE DIRECTIONS for the snake to move: RIGHT, LEFT, UP, DOWN.

The coordinates of the snake's body are determined by its dot size and its initial position.

When the snake moves in a particular direction, only the head's X-coordinate changes, while the other dots follow their previous position.

The X-coordinate of each dot in the snake's body decrements by its slot size if it is moving in the left direction and increments if it is moving in the right direction.

The Y-coordinate of each dot in the snake's body decrements if it is moving in the upward direction and increments if it is moving in the downward direction.
The head's position is determined by subtracting the dot size from its X-coordinate if it is moving in the left direction.

The position of each subsequent dot in the snake's body is determined by subtracting 1 from its X-coordinate if it is moving in the left direction.





* Functionalities Snake game built using Java and GUI made by using Java swing library. A user can provide directions to the snake using arrow keys and make it eat food. Also if the snake collides with the border or body, the game gets over and score gets displayed to the user, also user can restart the game using space bar.



IMAGES FROM THE DEVELOPED SNAKE GAME.


![snake 1](https://github.com/Vedango7/SnakeGame/assets/137282103/32d00950-a321-4b30-ac6b-7ca93670c3f7)
![Snake 2](https://github.com/Vedango7/SnakeGame/assets/137282103/8a124612-20e8-4909-9e84-a9648521b342)
![snake 3](https://github.com/Vedango7/SnakeGame/assets/137282103/4787fb35-f80d-4012-8638-2c0b7461f2ca)

