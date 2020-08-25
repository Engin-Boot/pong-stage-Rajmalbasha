
# Inter Modular Intraction

## Start state module

There are 3 situations Possible

* First time installation and new user. User choose to sign up it
will trigger **new user module**

* Existing user and new installation. Upon entering valid username
and password load user profile and trigger **Menu module**

* Existing app and already signed in. Just trigger **Menu module** and
load signed in users profile

## new user module

* Triggered when sign up is pressed in **start state module**

## Menu module

* Triggered upon signing in or upon opening game. Contains buttons
for new game, resume game, profile, settings, logout, delete account.
Upon pressing buttons corresponding module are triggered

## New game module

* Triggered upon pressing new game in **Menu module**. User first enters
desired time limit and select one among **versus computer**, **second player**.
Upon choosing second player in previous step user enters second player name and
it will then trigger **play game module**
