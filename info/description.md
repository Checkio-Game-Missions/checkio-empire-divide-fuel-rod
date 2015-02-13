Our goal is to divide the fuel rod in several pieces. The length of the rod is **N** metres.
All of the parts should have integer lengths (1, 2, 3 .. metres, but not 1.2).

You should divide the stick so that the lengths form 
the consecutive fragment of [the Triangular numbers](http://en.wikipedia.org/wiki/Triangular_number) 
series with the maximum quantity (fragment's length).
The parts should have different lengths (no repeating).
For example: **64** should divided at **15, 21, 28**,
because **28, 36** is shorter and **1, 3, 15, 45** is not a consecutive fragment.

You are given a length of the stick (N).
You should return the list of lengths (integers) for the parts in ascending order.
If it's not possible and the problem does not have a solution, then you should return an empty list.

![Rods](sawing.png)
