https://leetcode.com/problems/unique-paths/

![1111](../images/robot_maze.jpg)

dp[i][j] = dp[i-1][j] + dp[i][j-1];


            |  dp[i-1][j]
 dp[i][j-1] |  dp[i][j]

 
