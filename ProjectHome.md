/
// Introduction to C++
// Name:        ODOH KENNETH EMEKA
// Project
/
HOW TO COMPILE THIS PROGRAM:
This program is licensed as an open software.The source code comes with an executable file.The user can run this executable file as a script.


First make sure that all the files are saved in the same folder.

Note: This makes use of the  GNU  compiler.This is code is stable and was comfortably tested on a linux machine.
However,since to specific OS hooks were used in this code.It show also work well for windows machines.




HOW TO RUN IT:

Open the command prompt. Then, from the command line, go to the location of the files.To run the program, type the word, "./adventure.exe" while in the same location as above.




HOW TO PLAY:

When the program is compiled and run as described above, a welcome message is displayed showing some informationa. The program ask only for your name as you don't need so much personal information just to play a game.

Each player starts from the "Jail room", which is the first room in the game. To get out of the jail the player has to find a key to open the door of the jail.

The key is permanently placed in item in the room.I thought of making the key randow to make the game more interesting but I dropped the idea as in real life scenerio.Key don't move around without human intervention.

Once the key is collected, player must use the command USE 

&lt;key&gt;

 TO 

&lt;door&gt;

 where key and door are both arguments to the respective commands. After the command is issued, the door is opened with the message "door opens". But player is still in the room. To leave the room, player uses the command, MOVE 

&lt;north&gt;

 where north is the argument is the argument to the command MOVE. Other arguments (east, west and south) exists but player cannot move in those directions.

After the above command is issued, player advances to the next room, which is the Monster room with the guarding monster. To escape, player has to attack the monster consecutively 5 times in order to kill it. The ATTACK 

&lt;monster&gt;

 command is used for this purpose. For each attack issued by the player, the monster attacks back. An attack may or may not be successful, both for player and monster. If monster succeeds in hitting player five times first, then player dies and game is over. But if it happens the other way around, then monster dies and player may move to the next room.

To advance to the next room, player has to issue the command MOVE 

&lt;north&gt;

, then player is in the final Finish room, where player is greeted and kissed by the beautiful princess. The kiss is then rudely interrupted and player is turned into a frog and game ends. The next player can then start from the jail as well.

NB: to end the game at any time, the command QUIT is issued with no arguments. If that command is given, the current player's game is ended and the next player can take over from the jail of course. But if the last player issues that same command, the entire game is ended.


NB:
you can only move forward and not backward.If you leave a room.You cannot re-enter it again.


Player must unlock cell door and defeat the guarding monster.
The areas of the game is :
_Jail room_Guarding room
_Finish room_

**The doors will be opened with a key.**Player searches and gets the key in the jail cell and uses key to unlock
the door.
**Player opens door and move north.**After move command,player moves to next room(Guardian monster room)
**When the player reaches the guardian room.He attacks the monsters 5 times to kill it.**Player dies if monster hits the player first for five time.
**Player moves only north**When the player reaches finish room.He will be congratulated by
princess.
**Players turns int frog.**

RULES OF THE GAME
**Player/monster hitpoint count to 5.**Probability of attack player/monster is 50%.
**Game is turn based.**

The game is designed to ensure that the player does limit typing.
This will make the game more interactive.


BUG REPORTS
This version is relatively stable on windows platform.it could could on other plateform
will limited guaranty.


INSTALLATION AND GETTING STARTED
This is very easy to set up.You should easily run the Application icon and run the console based game.

IMPORTANT KNOWN PROBLEMS
No problems were found during testing.However,if user see any signifant bug.
Feel free to reach me on kenluck2001@yahoo.com

COPYRIGHT INFORMATION
This is a free ware.You are free to modify the codes without informing the owner.


This is a beta version of the software.The final version will be released in no time.



THE BRIEF DESCRIPTION OF THE COMMANDS:
You will have to get a clearer understanding of these commands by playing the game.
Here is a summary of the commands:

HELP: 	This displays the commands that are available to player.
COOMAND: This is used to display a list of COMMMANDS.

LOOK: 	This is used to give a description of the current room where a player is at the moment.eg look jail,look monster,look finish

SEARCH:	This is used to search the rooms to see the items.
SEARCHITEM:This is used to search the specific items in that room

EXAMINE: This is used to get the description of the composition of the room.e.g "examine jail" This will tell us what the jail is made up of.

EXAMINEITEM: This is used to get the description of the composition of the items room.e.g if the jail has a plate and we want to examine the plate .we use "examineitem plate"

MOVE:	Is used to move in a particular direction. The direction to move is supplied as an
> arguement to the command e.g. north.

ATTACK: Is used to attack the guarding monster at the monster room. The object to attack is
> supplied as an argument to the command. Attack is turn based though. An attack may or may not be successful.

USE:	This is used to use a tool or object that the player possesses on / to an object in the
> game e.g. to use the key to open the door. It also has an optional additional command TO which takes an argument as well e.g. to open the door, USE 

&lt;key&gt;

 TO 

&lt;door&gt;

 is issued after player possesses the key with the examine command.

QUIT:	This command ends the game of the current player or ends the game entirely if the current.This displays the exit message.


  * ENJOY