this program is a recursive maze solving algorithm.
the program take a maze and return the path that solve the maze.
you can change the maze status go to ExitFromMazeData.inc
define your maze status.
you can change the board size .

explanation
00  00  00  00  01  01  01  00  00
00  01  01  00  00  01  01  01  01
00  00  53  01  00  00  00  00  01
00  01  01  01  01  01  01  00  01
00  00  00  00  01  45  00  00  00

00: you can to move to this piece in the board 
01: you can not move to this piece in the board 
53: starting place initial state
45: goal state your target to reach this piece 

The path from S to E is :LLUURRRDRDRRRDDLL 
track the path step by step you can go out from the maze safely.

not all the mazes have a solving 
