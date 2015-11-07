# tournament
For my tournament project

Basically this includes some files to keep track of tournament 
pairings in a swiss pairing style format.

tournament.sql contains the postresql statments to set up the database.
It can be utilized by starting the postgresql shell with the command: psql
once in the shell run the following commands:
=> CREATE DATABASE tournament
=> \i tournament.sql

The first is the create the tournament database and the second is to 
create tables and views

After you have created the database and tables, you can run tournament_test.py and
tounament_test_odd.py to test the tournment .py code for an even number of players
and odd number of players respectively.
