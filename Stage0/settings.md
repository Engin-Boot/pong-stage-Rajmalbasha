
# Features : Music on/off, Background theme, change ball, change paddle size

## Acceptance criteria

## Scenario : user wishes to turn on/off game music

Given : Application is working, user is signed in, and user clicks settings button

When : user toggles between on and off button

Then : On music if initially is in off position and same as in opposite situation

## Scenario : User wishes to change background theme

Given : Application is working, user in signed in, and user clicks settings button

When :  user clicks background theme

Then : show different background themes and reward points required to apply
the particular theme. User chooses one theme and is eligible then reduce
reward points and apply the particular theme

## Scenario : User wishes to change pong

Given : Application is working, user in signed in, and user clicks settings button

When :  user clicks change ball button

Then : show different pongs available and reward points required to obtain
particular ball. User chooses one pong and is eligible then reduce reward
points and use the particular pong

## Scenario : User wishes to change paddle size

Given : Application is working, user in signed in, and user clicks settings button
,minimum and maximum paddle size are fixed

When : user clicks change paddle size and change the paddle size slider

Then : change the paddle size and use the new paddle
