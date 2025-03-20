this is the first glimpse of idea/framework/flowchart of how (i think) i am going to tackle this, javascript wise, not the HTML or CSS wise.

1. i need function that house the game,
   -> this function first, clear the board,
   -> in this function have a playround function.
2. in playround..
   -> first is checking the winner, if winner exist, winner is announce, and next instance is redo the main function that play the game.
   -> i will set default to player 1 to play its turn, where he choose a grid number of 1-9,
   -> everytime he done choosing, the grid is updated(render) and the winner is check again.
   -> WHISLT no winner, playround is replayed, after wapping player's turn
3. in winner deciding method,
   -> there is pattern check(easy way) or math check(I havent think about this but this may be less lines of code)
   -> if pattern met, whomever turn it is on (before swapping), then winner is decided, and the game is over
   -> if pattern does not met and the board is full, then TIE is happening, and the game is still over.

to that extend, these are function or method that I need to write.

a. winner deciding
a1. including check pattern, with IF board full then TIE
b. rendering the grid,
c. taking input and storing the input (to be rendered/to run RENDER grid everytime input is accepted)
d. swapping player (should be just like if player === A :  player B else player A, i guess)
e. play round method to house function c and d, with WHILE function that trigger everytime game is not over.
f. the clear board funtion, within the MAIN GAME function.


other things to consider (not urger maybe, idk):
1. bot AI that randomly do the moves,
2. reset game
3. starting input where we can choose who goes first or what marker we want.

that is all about the javascript i think..... the rest is about html and css to make all functioned, i guess.

# stunning-tictacktoes
stunning practice of creating game. like I am literally stunned of my incompetences
