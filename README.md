# kataMower

KataMower aims is to provide an java implementation for the Mower exercise
# Specifications 
Here is the English translation of the text you provided:

The company "MowItNo"w has decided to develop an automatic lawn mower, intended for rectangular surfaces. 
The mower can be programmed to cover the entire surface. 
The position of the mower is represented by a combination of coordinates (x,y) and a letter indicating the orientation according to the English cardinal notation (N,E,W,S). 
The lawn is divided into a grid to simplify navigation.
  For example, the position of the mower can be “0, 0, N”, which means that it is located in the lower left corner of the lawn, and oriented towards the North. 
To control the mower, a simple sequence of letters is sent to it. possible letters are “D”, “G” and “A”.
“D” and “G” rotate the mower 90° to the right or left respectively, without moving it. 
“A” means that the mower moves forward one square in the direction it is facing, without changing its orientation. 
If the position after movement is outside the lawn, the mower does not move, retains its orientation, and processes the next command.
It is assumed that the square directly to the North of the position (x, y) has coordinates (x, y+1).
An input file is required to provided the mower navigation:

The first line of the file gives the coordinates of the upper right corner of the lawn( coordonates of the lower left corner are assumed to be (0,0). 
● The rest of the file allows you to control all the mowers that have been deployed.
So Each mower has two lines dexribint its mouvements :
-> the first line gives the initial position of the mower, as well as its orientatio: 2 digits for position and orientation and a letter for the orientation (separated by a space) 
-> the second line is a series of instructions ordering the mower to explore the lawn:  The instructions are a sequence of characters without spaces. 
Each mower moves sequentially.
When a mower completes a series of instructions, it communicates its position and orientation.

# Objectives
Design and write a program with the unit tests in your favorite language to implement the movements of lawn mower by following above specifications

“Write a program in your preferred language to implement the movements of the lawn mower by following the specifications above.”
