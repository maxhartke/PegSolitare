# [PEG-SOLITAIRE-GAME-CS300](https://cs300-www.cs.wisc.edu/wp/peg-solitaire/)

This assignment has been designed as a self-assessment for students considering enrollment in CS300.  Our expectation is that well prepared students should be comfortable completing an assignment like this within two weeks (or about 15 hours, since CS300 is a 3 credit class).

Although students will use Java to complete their CS300 assignments, this self-assessment can be completed in whatever language you feel most comfortable working.  Students with sufficient experience in languages like: C, C++, Javascript, Python, Matlab, and others can expect to find many familiar data types and control structures in Java.  Experience with designing, implementing, testing, and debugging code written in these kinds of languages should transfer nicely toward developing code in Java.  You’ll note in the required organization below that your solution will be in a more procedure-oriented rather than object-oriented form.  This is because the later organizational paradigm will be taught in CS300.

The rest of this document is organized into the following sections:

The Rules of Peg Solitaire – The rules of the game you are implementing for this assignment.
Organizational Requirements – How your solution to this assignment must be organized.
Sample Runs – Demonstrate the output of a working implementation.
Code Templates – Files containing method stubs, ready for you to implement.
THE RULES OF PEG SOLITAIRE
Peg solitaire is a board game (or puzzle) in which a single player takes turns removing pegs from a board until either: they have removed all but the final peg to win the game, or they have lost because there are no legal moves left for them to make despite more than one peg remaining on the board.  The number of pegs and board-shapes vary, but these pegs are always set into holes arranged in a grid on the board.  A legal move involves jumping one peg over a neighboring peg to rest in a hole on the other side, and then removing the peg that was jumped over.  Diagonal jumps are not allowed.  In the following examples, an at sign (@) is used to represent the position of pegs, and a dash (-) is used to represent the position of an empty holes.

In the example above, the first turn involves moving the peg from the upper-left corner of the board, over the peg in the top-middle position, and landing in the hole in the upper-right corner.  The peg in the top-middle position is then removed, since it was jumped over.  Can you follow the subsequent moves starting with the lower-left peg on turn 2, lower-right peg on turn 3, and upper-right peg on turn 4?  After this sequence of moves, there are no more legal moves to be made.  And since there is more than one peg left on the board, this example demonstrates a lost game.

More information about this game is available on [Peg Solitaire Game on Wikipedia](https://en.wikipedia.org/wiki/Peg_solitaire).

