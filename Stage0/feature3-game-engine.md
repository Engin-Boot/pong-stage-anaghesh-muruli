# Game Engine Controller

## Feature #3

Controlls core gameplay

## Acceptance Criteria

### Scenario #1: initilize game engine

  Given the player is in the lobby

  When the player clicks start game

  Then initilize the game engine and setup the enviroment 
  
### Scenario #2: start game

  Given the game engine is initialized

  When the environments are loaded

  Then start the game

### Scenario #3: Check ball-wall collision

  Given the game has started

  When the ball misses paddle and collides the wall
  
  Then notify score handler module
  
  
### Scenario #4: set paddle size

  Given the game is started

  When the player gains 3 consecutive points
  
  Then increase the paddle size by 10 percent
