# 学习总结
#### 深度优先和广度优先  
DFS和BFS的代码模板要写熟练，DFS 可以使用栈或者递归实现，BFS可以使用队列实现
leetcode 102题 可以尝试使用DFS求解。
DFS/BFS代码模板(牢记)

#### 贪心算法:可以解决一些最优问题  
贪心算法可以解决一些最优化问题，比如：求图中的最小生成树、求哈夫曼编码等。对于工程和生活中的问题，贪心算法一般不能得到我们想要的答案。  
一旦一个问题可以通过贪心算法来解决，那么贪心算法一般是解决这个问题的最好方法。由于贪心算法的高效性以及其所求得的答案比较接近最优结果，贪心算法也可以用作辅助算法或者直接解决一些要求结果不是特别精确的问题。  

使用场景：最优子结构：通过子问题的最优解可以推到全局最优解  
贪心算法应用：
1.可以证明贪心算法可以得到全局最优解
2.贪心算法的角度：可能是从前向后贪心，可能是从后向前贪心，也可能是从某个局部切入贪心。

贪心算法 vs 动态规划：
贪心算法会对每个子问题的解决方案都作出选择，且不能回退。
动态规划会保存以前的运行结果，根据以前的运行结果来对当前的情况进行选择，可以回退。

贪心：当下局部最优解，不能回退
回溯：可以回退
动态规划：最优判断且能回退。

洪水算法(FloodFill)：每次看到岛屿，就把这个连在一起的岛屿夷为平地。

#### 二分查找：
二分查找最关键的三个前提条件：[单调 上下界 索引]  
1.目标函数单调性(单调递增/递减)
2.存在上下界(bounded)
3.能够通过索引访问(index access)
代码模板：


  

