
# Features : Select versus computer, second player, option to choose play time

## Acceptance criteria

## Scenario : Choosing play time

Given : Application is working, user is signed in, chooses new game

When : user selects newgame

Then : first ask the play time

## Scenario : Second player is present

Given : Application is working, user is signed in, chooses new game
and sets play time

When : user chooses second player option

Then : ask for second person name and start the game

## Scenario : Versus computer

Given : Application is working, user is signed in, chooses new game
and sets play time

When : user chooses versus computer option

Then : fire up the game with computer as second player
