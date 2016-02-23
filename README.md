# TicTacToe

Tic-Tac-Toe the Game<br>

- TG 12/06/2015(modifed oct/2015)<br>
- project for PoC course by Rice University<br>
https://www.coursera.org/course/principlescomputing1<br>
-TicTacToe template<br>
http://www.codeskulptor.org/#poc_ttt_template.py<br>

Console-based interface and graphical user interface provided by instructors("TTTBoard class", "TicTacGUI class") 
and modified by TG(short game instruction added)

<p>
!!!! NOTE !!!!<br>
This is PYTHON code written to work in codeskulptor, w'll work in PYTHON 2.X after some changes<br>
Code from text file must be copied and paste into codeskulptor editor: http://www.codeskulptor.org/<br>
popup windows must be enabled<br>
# Be patient, it w'll take up to 20 seconds for AI to make 
a move on 9 square board with 1000 trials 
(greater board/trials longer will take)
</p>

<p>
Tic-tac-toe(also known as Noughts and crosses or Xs and Os) 
is a game for two players, X and O, who take turns marking 
the spaces in a 3x3 grid where X always go first. 
The player who succeeds in placing their marks in a 
horizontal, vertical, or diagonal row (through all the 
grid) wins the game.
In this version you can play against machine player only 
or watch machine vs machine, also this version be able to 
handle any square grid and 'reverse game mode variant' 
 ('lose' if get the row). 
Machine player use a Monte Carlo simulation to decide its next move:<br>
https://en.wikipedia.org/wiki/Monte_Carlo_method<br>
</p>

- enable pop-up windows!!<br>
- to change AI level - change value of NTRIALS in the code<br>
- to change board size - change value of BOARD_SIZE in the code<br>
- to change game variant - change value of game_mode == True<br>
- player starts (with X), if you want AI to make first move change PLAYERO to PLAYERX in run_gui (last line of the code)<br>
- uncomment play_game and comment out run_gui to see machine player play against itself in the console<br>
- Hit PLAY icon to Start (left top corner)
