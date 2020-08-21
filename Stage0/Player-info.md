# Player info

## Feature

Accept and verify Player information

## Acceptance Criteria

### Scenario: Create new player

  Given the player is not exisiting 

  When the player clicks create player

  Then accept userName and email

### Scenario: verify the player

  Given the player is already registered 

  When the player types his userName 
  And clicks proceed

  Then verify if the userName is registered

### Scenario: get player details

  Given the player is verifed and authenticated

  When the player logs in
  
  Then get the information about the player
  And store in the session
