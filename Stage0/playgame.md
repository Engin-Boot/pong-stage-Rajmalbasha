
# Features  : Keeps score of players, timer, back to home, pause button

## Scenario : user wants to go back to home page

Given : application is working, user is signed in and playing

When : user click back button on the screen

Then : come back to home page and don't end the game

## Scenario : user wants to pause the game

Given : application is working, user is signed in and playing

When : user clicks the pause button

Then : stay in the same page and pause the game

## Scenario : user wants to start the paused game

Given : application is working, user is signed in, playing and game is paused

When : user clicks the pause button

Then : resume the game again

## Scenario : Timer times out

Given : application is working, user is signed in and playing

When : timer times out

Then : end the game and declared player with highest score as winner

## Scenario : player scores a point

Given : application is working, user is signed in and playing

When : ball doesn't touch the oppnents paddle

Then : Increment the player point by 1

## Scenario : Reward points

Given : application is working, user is signed in, played the game

When : user wins the game

Then : calculate the reward points based on number of times 2 points are
obtained consecutively,number of times 3 points are obtained consecutively,
number of times 4 points are obtained consecutively,number of times 5 points
are obtained consecutively
