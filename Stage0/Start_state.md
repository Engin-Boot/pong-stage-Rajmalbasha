
# Features

New user sign up, Existing user sign in, Existing user opening already
installed application

## Acceptance Criteria

## Scenario : New user sign up

Given : Application is newly installed on the phone and new user playing

When : user clicks new user register button

Then : trigger new user module

## Scenario : Existing user sign in upon reinstalling

Given : Application is reinstalled on the phone and existing user opened it

When : user enters valid username and corresponding password

Then : load the details of the user

## Scenario : Application restarts with sign in page cause of interrupt

Given : Application is installed and user is playing or opening the application

When : interrupt occurs

Then : enter the valid sign in details

## Scenario : Application restarts after updating

Given : Application is installed and already in use

When : update is available and user updates the application

Then : ask the user to enter valid sign in details again

## Scenario : Existed user opening the apllication

Given : Application is installed and in use for many days

When : user opens the application

Then : automatically load user details and open menu
