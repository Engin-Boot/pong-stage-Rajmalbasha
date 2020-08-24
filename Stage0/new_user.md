
# Features

Take the details of the new user --> Name, Username, Email, Password

Option to sign in using Gmail or facebook

## Acceptance criteria

## Scenario : username is not availale

Given : Application is installed and user is newly registering

When : user enters username already taken

Then : Display username already taken try another username

## Scenario : Chooses to sign in using Gmail

Given : Application is installed and user is newly registering

When : user choose option sign in using Gmail

Then : create new user profile using the Gmail

##Scenario : Using exist mail id to create new account

Given : Application is installed and user is newly registering

When : enters Gmail for which already an account is present

Then: redirect to main sign in page
