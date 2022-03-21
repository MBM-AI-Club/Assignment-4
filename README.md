# Assignment 4

Q. Use recursion to design a program that can automatically place its chance in the previously built tic-tac-toe game and always wins the game.
Hint: https://www.neverstopbuilding.com/blog/minimax

Example:
```
In: 
Choose X or O
Player: X

Player: 4
Out:
   |   |
-----------
   | X |
-----------
   |   |

Out: 
Computer places O at 2
   |   | O
-----------
   | X |
-----------
   |   |

In: 
Player: 0
Out:
 X |   | O
-----------
   | X |
-----------
   |   |
   
Out: 
Computer places O at 9
 X |   | O
-----------
   | X | 
-----------
   |   | O

In:
Player: 5
Out: 
 X |   | O
-----------
   | X | X
-----------
   |   | O

Out: 
Computer places O at 3
 X |   | O
-----------
 O | X | X
-----------
   |   | O

In:
Player: 1
Out: 
 X | X | O
-----------
 O | X | X
-----------
   |   | O
   
Out: 
Computer places O at 7
 X | X | O
-----------
 O | X | X
-----------
   | O | O

In:
Player: 6
Out: 
 X | X | O
-----------
 O | X | X
-----------
 X | O | O

The match is drawn!!!
```
