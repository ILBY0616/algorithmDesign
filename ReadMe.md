1. **递归（Recursion）**：
    - **定义**：递归是一种在算法中自我调用的方法，它将问题分解成更小的子问题来解决。
    - **特点**：简洁的代码实现，但可能存在效率问题，如栈溢出和重复计算。
    - **应用**：适用于问题可以分解为相似子问题的场景，如树的遍历、分治算法等。

2. **递推（Dynamic Programming）**：
    - **定义**：递推是一种通过将问题分解成更小的子问题，并存储这些子问题的解（通常是在表格中），以避免重复计算的方法。
    - **特点**：通常比纯递归更高效，因为它避免了重复计算。
    - **应用**：适用于具有重叠子问题和最优子结构特性的问题，如斐波那契数列、背包问题等。

3. **迭代（Iteration）**：
    - **定义**：迭代是一种重复过程，通过循环结构来实现。
    - **特点**：通常比递归更高效，因为它避免了函数调用的开销。
    - **应用**：适用于需要重复执行相同操作的场景，如排序算法、搜索算法等。

4. **分治（Divide and Conquer）**：
    - **定义**：分治是一种将问题分解成多个小问题，递归解决这些小问题，然后将结果合并的策略。
    - **特点**：可以并行处理，适合快速解决问题。
    - **应用**：适用于可以分解为独立子问题的场景，如快速排序、归并排序等。

5. **贪心（Greedy）**：
    - **定义**：贪心算法是一种在每一步选择中都采取在当前状态下最好或最优的选择，以期望导致结果是最好或最优的算法。
    - **特点**：简单高效，但不总是能得到全局最优解。
    - **应用**：适用于可以局部最优推出全局最优的问题，如霍夫曼编码、最小生成树等。

6. **动态规划（Dynamic Programming）**：
    - **定义**：动态规划是一种通过将问题分解成重叠子问题，并存储这些子问题的解以避免重复计算的方法。
    - **特点**：适用于具有重叠子问题和最优子结构的问题，通常比贪心算法更复杂。
    - **应用**：同递推。

7. **回溯（Backtracking）**：
    - **定义**：回溯是一种通过试错来寻找所有可能解的算法，当确定某一部分解不可能是最终解时，就回退到上一步。
    - **特点**：可以找到所有可能的解，但可能效率较低。
    - **应用**：适用于需要搜索所有可能解的问题，如八皇后问题、数独等。

8. **分支限界（Branch and Bound）**：
    - **定义**：分支限界是一种在搜索解空间时，通过系统地枚举解空间的部分或全部节点，来寻找一个目标解或所有解的算法。
    - **特点**：通过限界技术减少搜索空间，提高效率。
    - **应用**：适用于需要在解空间中寻找最优解的问题，如旅行商问题、背包问题等。
