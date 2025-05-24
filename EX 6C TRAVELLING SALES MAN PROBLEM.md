# EX 6C TRAVELLING SALES MAN PROBLEM
## DATE: 03/05/2025
## AIM:
To Solve Travelling Sales man Problem for the following graph.

![image](https://github.com/user-attachments/assets/653921a4-3d7b-4691-9b41-735e80f7af0b)



## Algorithm
1. Represent the graph as a cost matrix dist[n][n], where dist[i][j] is the cost to go from city i to city j.

2. Create a DP table:
    dp[mask][i] = minimum cost to reach city i having visited cities in mask (a bitmask of visited cities).

3. Initialize:

   dp[1 << 0][0] = 0 — start from city 0 with only city 0 visited.

4. Fill DP table:

    For all bitmasks mask, for all cities i in mask, update:
   dp[mask][i] = min(dp[mask][i], dp[mask ^ (1 << i)][j] + dist[j][i])
   for all j in mask where j != i.

5. Get result:

   The final answer is:
   min(dp[all_visited_mask][j] + dist[j][0])
   for all j ≠ 0, where all_visited_mask = (1 << n) - 1
   

## Program:
```
/*
To implement the program for TSP.


Developed by: 
Register Number:  
*/
```

## Output:



## Result:
Thus the program was executed successfully for finding the minimum cost to vist all cities.
