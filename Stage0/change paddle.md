
# Features : change paddle size between prefixed minimum and maximum,
option to choose between different paddle

## Scenario : User wishes to change paddle size

Given : Application is working, user is signed in,and wishes
to change paddle from settings

When : user move paddle size slidder between minimum and maximum

Then : apply changes and display on game board

## Scenario : user wishes to change paddle

Given : Application is working, user is signed in,and wishes
to change paddle from settings

When : user choose particular paddle property

Then : check reward points and see user is eligible

## Scenario : sufficient reward points are available

Given : Application is working, user is signed in,and wishes
to change paddle from settings

When : user choose particular paddle property

Then : reduce reward points of the user and reflect the new properties
in the game board

## Scenario : No sufficient reward points

Given : Application is working, user is signed in,and wishes
to change paddle from settings

When : user choose particular paddle property

Then : display no sufficient reward points to apply property

