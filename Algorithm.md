## **Basic Game Algorithms**

**Paddle Movement Algorithm**
1. Paddle Spawns Middle of the Game Screen
2. Player clicks and holds the Right Arrow key on their keyboard 
3. The paddle continuously moves towards the Right side of the game screen
4. Player lets go of the Right Arrow key on their keyboard
5. Paddle ceases movement at its current position
6. Player clicks and holds the Left Arrow key on their keyboard
7. The paddle continuously moves towards the Left side of the game screen
8. The Player lets go of the Left Arrow key on their keyboard
9. The paddle ceases movement at its current position

**Ball Movement Algorithm**
1. Ball spawns a small distance between the top surface of the paddle and middle of the screen
2. Player starts the game (by clicking the start button)
3. Ball begins to fall towards the surface of the top surface of the paddle
4. Paddle hits the surface of the paddle and bounces the opposite direction of its initial movement
5. Paddle hits the surface (top / sides / bottom) of a brick, sides and top of the game screen or any surface of the paddle
6. The ball moves the opposite direction of the initial movement or move according to basic game physics (angles and such)
7. The ball falls past the paddle and towards the bottom section of the screen
8. The ball despawns (and possibly resets depending on user input in the Game Over Screen)

**Brick Algorithm**
1. Bricks (including the power-up bricks) Spawn in the game on the top half of the game screen
2. If a regular brick is hit by the ball (any surface of the brick) the brick breaks
3. If a power-up brick gets hit by the ball, a JPEG or Image of a power-up falls down
4. If the player collects the power-up, activates power-up
5. If all of the bricks have been hit, move to a new level or reset the game (or a game completed screen pops-up)
