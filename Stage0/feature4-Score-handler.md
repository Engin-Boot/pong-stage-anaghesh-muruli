# Score Handler

## Feature #4

handles scores of the game

## Acceptance Criteria

### Scenario #1: update score when a player misses the ball

  Given the game is in progress

  When a player miss the ball

  Then increment the opossite player's score
  
### Scenario #2: get the currect score 

  Given the game is in progress

  When the score is requested to update UI

  Then send the score

### Scenario #3: set the maximum score

  Given the game has not started yet and the player is logged in

  When the player increases the max score
  
  Then update the maximum score
  
  
### Scenario #4: check winner 

  Given the is in progress and score is updated

  When the current score is equal to maximum score
  
  Then notify Winner module with the winner's name
