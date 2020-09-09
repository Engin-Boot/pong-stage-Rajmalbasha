
# Feature : Can choose different types of ball

## Scenario : change ball properties

Given : Application is working, user is signed in,and wishes
to change ball from settings

When : user selects to change ball

Then : Check reward points and see user is eligible or not

## Scenario : Sufficient rewards points are available

Given : Application is working, user is signed in,and wishes
to change ball from settings

When : user selects particular property

Then : reduce reward points and apply new properties

## Scenario : No sufficient reward points

Given : Application is working, user is signed in,and wishes
to change ball from settings

When : user selects particular property

Then : display no sufficient reward point to apply particular property
