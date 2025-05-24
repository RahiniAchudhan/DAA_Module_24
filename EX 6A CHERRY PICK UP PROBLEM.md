# EX 6A CHERRY PICK UP PROBLEM
## DATE:
## AIM:
To Create a python program for the following problem statement.
You are given an n x n grid representing a field of cherries, each cell is one of three possible integers.
0	means the cell is empty, so you can pass through,
1	means the cell contains a cherry that you can pick up and pass through, or
-1 means the cell contains a thorn that blocks your way.
Return the maximum number of cherries you can collect by following the rules below:
Starting at the position (0, 0) and reaching (n - 1, n - 1) by moving right or down through valid path cells (cells with value 0 or 1).
After reaching (n - 1, n - 1), returning to (0, 0) by moving left or up through valid path cells.
When passing through a path cell containing a cherry, you pick it up, and the cell becomes an empty cell 0. If there is no valid path between (0, 0) and (n - 1, n - 1), then no cherries can be collected.



## Algorithm
1.Start at (0, 0), move to (n-1, n-1) (only right or down)

2.Then return back to (0, 0) (only left or up)

3.Can pass through cells with 0 or 1

4.Can pick cherries (1) only once (cell becomes 0 after pick)

5.Avoid thorns (-1) 
  

## Program:
```
/*
To implement the program for Cherry pickup problem.


Developed by: 
Register Number:  
*/
```

## Output:



## Result:
Thus the above program was executed successfully for finding the maximum number of cherries from grid.
