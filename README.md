# Checkers-in-Assembly
Checkers in PDP-11 Assembly

This project was created for homework in Atam course in Technion University, as a final project.

This is a working project, made for the PDP-11 simulator.
I uploaded both the .s11 and .o11 files.

Anyone who wishes to use this code, can use it freely.

If you have any questions about the code, let me know.


# Instructions

The game works via 4 commands: 

1. start U XX U XX  - (U - is either c (computer) or h (human) / XX - a decimal number that indicates the seconds that each player has in their turn) the first user is the white player, the second user is black.

2. move PP PP - moving a piece of the human player in its turn, PP is an OCTAL number,indicates the place of the piece on the board (top left is 00). The first number indicates the origin, and the second is the destination.

3. time - the time left for current game will be printed on the screen.

4. stop - current game is stopped and the winner is printed on the screen.

- If the command wasn't typed in the format above, or an illegal command had been typed, it will be printed on screen.

- First, the user should start the game with the start command above.

- If its the computers turn to play, the best move would be calculated via minmax algorithm, until its turn time hasn't ran out.

- If the human's player time ran out, the game is over.


Good luck, and I hope you enjoy the game.
