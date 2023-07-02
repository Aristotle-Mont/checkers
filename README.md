# checkers_game
game rules
position rules

[X] pieces are only on black square.
[X] only 1 piece can stay in black square.
game initialization rule

[X] 2 players game
[X] player are either black or white
[X] black player initalization rows are 0,1
[X] white player initalization rows are 6,7
[X] pieces of players initalization rows must fill all valid position.
territory rules

[X] territory of black player is 0
[X] territory of white player is 7
move rules

[X] piece must be on the board after execute a move
[X] one player can move 1 piece per turn.
[X] piece have 2 type of moves: step or jump.
[X] piece can only be moved if its position after move is not invalid.
[X] piece step when no other piece is within (+-1, +1).
[X] piece jump over other piece to (-2,+2) when the piece is within ( -1, +1) of other pieces.
[X] when a piece jump over opponent piece, opponent piece is not removed.
termination rules

[X] first player who has a king win immediately
