# 递归
递归就是把一个要解决的大问题分解成一个或者多个相同原理的规模更小的子问题，通过函数自身调用逐层向下拆解，直到子问题可以直接解决，再把所有的解合并起来得出大问题的答案。

递归代码实现必须包含：
  1.终止条件（base case）问题小到如何可以直接解决。
  2.递推关系 递归实现的公式大问题和子问题之间的关系。

经典案例：阶乘、斐波那契数列、分治算法

以阶乘为例：
从 1 开始，连续一串正整数乘到这个数本身**，数学上用感叹号!表示。

举个例子：
5 的阶乘（写作 5!）= 1 × 2 × 3 × 4 × 5 = 120

由此得出：
阶乘的定义是：n! = n * (n-1) * ... * 1
终止条件是：n <= 1
递推关系是：n! = n * (n-1)!

---

# Recursion
Recursion is an approach to solving a large problem by breaking it down into one or more smaller subproblems that follow the same principle. It drills down layer by layer through self-calls of the function, until the subproblems can be solved directly, then combines all sub-solutions to derive the answer to the original problem.

A recursive code implementation must include:
1. **Base case**: the condition where the subproblem is small enough to be solved directly.
2. **Recurrence relation**: the formula for the recursive implementation, which defines the relationship between the larger problem and its subproblems.

Classic use cases: factorial, Fibonacci sequence, divide-and-conquer algorithms.


Take factorial as an example:
The factorial of a number is the product of all positive integers starting from 1 up to that number, denoted by the exclamation mark ! in mathematics.

For instance:
The factorial of 5 (written as 5!) = 1 × 2 × 3 × 4 × 5 = 120

It follows that:
Definition of factorial: n! = n × (n−1) × ... × 1
Base case: n <= 1
Recurrence relation: n! = n × (n−1)!