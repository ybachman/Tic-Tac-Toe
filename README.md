# Tic-Tac-Toe
C++ console program in which a user may play tic-tac-toe against another player or the computer.

Upon startup, users may create an account, login to an existing account, or play as a guest. If played as a guest, no record of wins, losses, and draws will be kept.

If played with an account, a record will be kept in a file for the number of wins, losses, and draws. Accounts continue to exist outside of program runtime, with account details stored in the "users.txt" file. Account records in the file are stored in this format:

First line: Total number of registered users (So far, 5)<br>
Username<br>
Password<br>
E-mail<br>
Wins<br>
Losses<br>
Draws

Once a user is logged in, or playing as a guest, they may chose to play against another player or the computer. If playing against another player is selected, an option for player 2 to log in or play as a guest is offered.

When two players are set up, or playing against the computer is selected, an option for the game board dimensions is offered. Users may play on the traditional 3 x 3 board, 4 x 4, or 5 x 5 board.

When the board is selected, two boards appear. The left board is where the X and O marks are placed, the right board places a number on each box as a refernce to simplify entering your mark into the left board.

When a winner or a draw is determined; the win, loss, and draw count is updated on the existing participating accounts (if applicable). 
