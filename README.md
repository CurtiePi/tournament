# tournament
For my tournament project

Basically this includes some files to keep track of tournament 
pairings in a swiss pairing style format.

It is primarily made up of 4 files:
tournament.sql contains the postresql statments to set up the database.
tournament.py contains the code to modify the database and administer the tournament.
tournament_test.py contains code to test tournament.py for an even numbe of players.
tournament_test_odd.py contains code to test tournament.py for an odd numbe of players.

To run this project:
cd tournament

Start the postgres shell:
$: psgl

Now that you are in the postgrsql shell you need to create the database: 
=> CREATE DATABASE tournament

Afterwards you can set up the database by importing the sql file:
=> \i tournament.sql

After you have created the database and tables, you can run tournament_test.py and
tounament_test_odd.py to test the tournment .py code for an even number of players
and odd number of players respectively.

$: python tournment_test.py 
$: python tournament_test_odd.py

Thank youy and happy gaming.
