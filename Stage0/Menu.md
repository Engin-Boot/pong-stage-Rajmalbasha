
# Features : New game, Resume, Settings, Statistics, Profile, Logout, Delete account

## Acceptance criteria

## Scenario : User choose to start new game

Given : Application is working, user is signed in

When : user clicks new game button

Then : trigger new game module

## Scenario : User choose to resume

Given : Application is working, user is signed in

When : user clicks resume button

Then : log the paused game details

## Scenario : User opt to go to settings

Given : Application is working, user is signed in

when : user click settings button

Then : trigger settings module

## Scenario : User wants to visit profile

Given : Application is working, user is signed in

When : user clicks profile button

Then : show all the details name, username, mail, photo

## Scenario : Report of all the games played

Given : Application is working, user is signed in

When : user clicks statistics button

Then : show all the details of game played till then wins and lost details

## Scenario : user opts to logout

Given : Application is working, user is signed

When : user clicks logout button

Then : logout from the account and come to sign in page

## Scenario : User wants to delete account

Given : Application is working, user is signed in

When : user clicks delete account button

Then : delete the user profile
