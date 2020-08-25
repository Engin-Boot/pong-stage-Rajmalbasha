
# Features : Music on/off, Background theme, change ball, change paddle size

## Acceptance criteria

## Scenario : user wishes to turn on/off game music

Given : Application is working, user is signed in, and user clicks settings button

When : user toggles between on and off button

Then : On music if initially is in off position and same as in opposite situation

## Scenario : User wishes to change background theme

Given : Application is working, user in signed in, and user clicks settings button

When :  user clicks background theme button

Then : trigger background theme module

## Scenario : User wishes to change ball properties

Given : Application is working, user in signed in, and user clicks settings button

When :  user clicks change ball button

Then : Trigger change ball module

## Scenario : User wishes to change paddle size

Given : Application is working, user in signed in, and user clicks settings button
,minimum and maximum paddle size are fixed

When : user clicks change paddle button

Then : trigger change paddle module
