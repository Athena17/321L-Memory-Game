# 321L-Memory-Game
Memory Game - An EECE 321L Course Project
--------------------------------------------------------------------------------------------------------------------------
As part of EECE 321L course, we were asked to design a memory game that consists of 6 matching pairs.
The cards will be labled alphabetically from A to F.
--------------------------------------------------------------------------------------------------------------------------

The game consists of 3 modes:

Mode 1:
 
 -> The game will end only if a player makes all matching pairs.
    Depending on the player's performance, the player will get a feedback as Super, Average or Weak.

Mode 2 

-> The game will be time dependent. The player should make matching pairs before the
   end of the game time. Then, the final score will be provided as a combination of the remaining
   time and the number of matches done. Also, in this mode, the game ends whenever the player
   makes all available matches or the time of game ends.

Mode 3:

-> An initial score will be set. Then every match, a point will be added to this score. 
After every non-matching pair, the system will check if the card were opened more than one time and failed to do a match, 
then a point will be deducted from the score for every re-opened revealed card.
The game will end if the player makes all the available matches or the player reaches the max number of opened
revealed cards.

--------------------------------------------------------------------------------------------------------------------------
This project is designed using Mplab IDE.
The project is implement with an LCD display using PIC16F4A microcontroller.
Proteus software was used for testing.
--------------------------------------------------------------------------------------------------------------------------

