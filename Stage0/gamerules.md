# Features : Handling the movements

## Scenario  : Increasing the ball speed

Given : Application is working, user is signed in and playing the game

When : ball touches the players paddle

Then : rebounce and increase the ball speed

## Scenario : Scoring a point

Given : Application is working, user is signed in and playing the game

When : ball doesn't touch neither one of the paddles and touches the
Extremes along the x axis

Then : Increase point for the player opposite to the particular extreme

## Scenario : Rebounce the ball

Given : Application is working, user is signed in and playing the game

When : ball touches the extremes along the y axis

Then : Rebounce the ball with the same speed
