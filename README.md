# tournament
For my tournament project

BACKGROUND:

Basically this includes some files to keep track of tournament 
pairings in a swiss pairing style format. The format pairs highest
ranked players against similarly ranked players. In cases with an odd
number of players, the higher ranked players are given a BYE, however 
no player gets more than one BYE for the competition and no two players
play each other more than once.

WHAT IS INCLUDED:

It is primarily made up of 4 files:
tournament.sql contains the postresql statments to set up the database.
tournament.py contains the code to modify the database and administer the tournament.
tournament_test.py contains code to test tournament.py for an even numbe of players.
tournament_test_odd.py contains code to test tournament.py for an odd numbe of players.

INSTRUCTIONS:

To download this project run the following command:

$: git clone https://github.com/CurtiePi/tournament.git tounament


To run this project change directory to the tournament directory:

$: cd tournament

Start the postgresql shell:

$: psgl

Now that you are in the postgrsql shell you need to create the database:

=> CREATE DATABASE tournament

Afterwards you can set up the database by importing the sql file:

=> \i tournament.sql

Exit the postgresql shell with the command

=> \q

Now that you have created the database and tables, you can run tournament_test.py and
tournament_test_odd.py to test the tournment.py code for an even number of players
and odd number of players respectively.

$: python tournment_test.py 

$: python tournament_test_odd.py

Thank you and happy gaming.
