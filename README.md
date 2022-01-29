# UOCIS322 - Project 3 #

A project using templates and flask to emphasize ajax and jquery interactions

## Installing and running

to install, simply fork and clone this repo. Build using the provided dockerfile, but change
that dockerfile so it uses your own credentials. You will also want to create a credentials
file called 'credentials.ini' filled out with your own information, and copied from the
structure of credentials_skel.ini. If you want to run this outside of a docker environment,
make sure that you have flask installed.

## The contents

This is a simple word identification game involving fining words from a given list that can
be composed from a provided jumble. Updating elements of the page should occur wihout a
re-render of the page, and should adress, accurately, the user's interaction with the game.

## Authors

Michal Young, Ram Durairajan. Updated by Ali Hassani.

Completed by Tammas Hicks
