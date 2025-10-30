Classic Snake Game :- This is a Snake game implementation using Python's turtle graphics module.

Game Setup :- 
1) Created in a 600x600 pixel black window with the title "Snake Game by @aalhadramteke"
2) Sets up a yellow square as the snake's head starting at the center
3) Places a red circle as food at position (0, 100)
Initializes score tracking with a display at the top of the screen

Game Mechanics :- 
1. The snake moves in 20-pixel increments
2. When the snake eats food (gets within 20 pixels):
A new green segment is added to the snake's body
Score increases by 10 points
Game speed slightly increases (delay decreases)
Food reappears at a random location
3. The game ends if:
The snake hits the border (beyond 290 pixels from center)
The snake collides with its own body
After game over, the snake resets to center position, segments disappear, and score resets to 0

The game runs in an infinite loop, continuously updating the screen and checking for collisions, making it a fully functional Snake game implementation.
