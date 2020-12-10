# Chess
This game requires Pygame to run. And before starting, go to line 57 of the Chess Code, and replace the x's with the location of the Image Files folder on your computer.
Make sure the Chess Code and Image Files are in the same folder.  Sorry for the hassle.
  
How To Play:

  To select a piece, click it.
  
  To deselect a piece, click it a second time.
  
  Available moves show up as light green squares, click on a light green square to move your piece there.
  En Passant and Castle moves show up as yellow squares, click on the square to perform the move.

  Press Space to make the robot execute a single move.  The robot works for both teams.

  There is a panel on the bottom with four buttons, click a button to activate its function.
  Only one button may be pressed at a time, and selecting a second button will deselect the first one.
  
  The functions of the buttons are as follows:
  
  Control: Displays all squares that a team can occupy in the next turn in red.  Your piece is at risk of capture if it's in a red square.
  
  Synergy: Displays the total number of friendly pieces protecting a piece as a shield value.  The shield value caps at 4, at which point the shield value becomes "4+".
           If your piece has a shield value of zero, it can be taken by the other team with no fear of retaliation.
