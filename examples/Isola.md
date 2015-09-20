# [Isola](https://en.wikipedia.org/wiki/Isola_(board_game))

Also known as: Isolation, Stranded.

Isola is a two-player board game. It is played on a 7x7 grid which is initially filled with squares. Both players have one piece; it is in the middle position of the row closest to his/her side of the board. Players can place their piece on empty squares only. 

<p align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/8/8a/Isola_starting_position.png"/>
</p>

A move consists of two subsequent actions:

1. Moving a piece to a neighboring (horizontally, vertically, or diagonally) position that contains an empty square.
2. Removing an empty square.

The player who cannot make any move loses the game.

Input 
---
The input is an 7x7 matrix consisting only of 0, 1, 2 and -1. Then another line follows with number 1 or 2, which is your player id. The difference between player 1 and 2 is that player 1 starts the game.

In the given matrix, top-left is (0, 0) and bottom-right is (6, 6). Rows increases from top to bottom and column increases from left to right. 

The cell marked 0 means it contains a square. The cell marked 1 means it contains player 1's piece. The cell marked 2 means it contains player 2's piece. The cell marked -1 means it doesn't contain the square.

Starting state
---
```
0 0 0 2 0 0 0
0 0 0 0 0 0 0
0 0 0 0 0 0 0
0 0 0 0 0 0 0
0 0 0 0 0 0 0
0 0 0 0 0 0 0
0 0 0 1 0 0 0
```

Sample input
---
```
0 0 0 2 0 0 0
0 0 0 0 0 0 0
0 0 0 - 0 0 0
0 0 0 0 0 0 0
0 0 0 0 0 0 0
0 0 0 1 0 0 0
0 0 0 0 0 0 0
2
```

Output 
---
The coordinates of the empty square (x, y) where you want to move your piece. 
In next line, the (x, y) coordinates of empty square to remove.

Sample output
---
```
3 5
3 2
```

Challenges
---
- [HackerEarth - Battle of Bots 2015](https://www.hackerearth.com/battle-of-bots/multiplayer/isola/)