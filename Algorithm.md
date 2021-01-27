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
1. Ball spawns a small distance between the top surface of the paddle and middle of the screen (Now spawns on top of the paddle)
2. Player starts the game (by clicking the enter key)
3. Ball begins to fall towards the surface of the top surface of the paddle (Immediately gets hit by the paddle now)
4. Paddle hits the surface of the paddle and bounces the opposite direction of its initial movement
5. Paddle hits the surface (top / sides / bottom) of a brick, sides and top of the game screen or any surface of the paddle
6. The ball moves the opposite direction of the initial movement or move according to basic game physics (angles and such)
7. The ball falls past the paddle and towards the bottom section of the screen
8. The ball despawns (and possibly resets depending on user input in the Game Over Screen)

**Brick Algorithm**
1. Bricks (including the power-up bricks) Spawn in the game on the top half of the game screen
2. If a regular brick is hit by the ball (any surface of the brick) the brick breaks
3. Player score goes up when brick is hit
4. When all of the bricks are hit, player wins game
5. Game restarts (if the enter key is pressed) unless player decides to exit the game

**Game Over + Game Start Frames**
1. Game Start Screen pops up on the player's screen (assuming there is no intro sequence)
2. Player selects / presses the enter key on their keyboard
3. Game Starts (See the Other Algorithms)
4. Player selects the exit button on the start screen
5. Player Exits the Game Start Screen (and the game in general)
6. Player loses the game (according to the way the ball algorithm mentions)
7. Game over screen pops-up on the player's screen (game over now includes player score)
8. Player presses the enter key again to restart
9. Game resets and returns to the start screen
10. Player selects exit game button
11. Player exits the game over screen (and the game in general)

**Challenges Algorithm**
1. Player begins the game (See Other Algorithms)
2. Each time the ball hits the paddle, a challenge will execute randomly
3. If a challenge is in play, the ball will speed up or slow down  or, the paddle will speed up or slow down 
4. If player wins and hits all of the bricks
5. Challenge will not be active

**Music Algorithm**
1. If player starts the game
2. Background music plays
3. Ball hits a brick
4. Soundeffect plays
5. Ball hits the paddle
6. Soundeffect plays

**Pause and Play Algorithm**
1. Player starts the game
2. If player clicks the space bar on their keyboard
3. Game pauses
4. If player clicks the space bar on their keyboard again
5. Gameplay resumes


