java c
Computational Optimization
Assignment #3
Problem 1
The following table specifies the weights and values per unit of five different products held in storage.  The quantity of each product is unlimited.
Product (i)     Weight per unit (wi) Value per unit (vi)
1
7
9
2
5
4
3
4
3
4
3
2
5
1
0.5A plane with a weight capacity of 13 is to be used, for one trip only, to transport the products. We would like to know how many units of each product should be loaded onto the plane to maximize the value of goods shipped.Use dynamic programming to find the optimal solution. Please provide the following details (a) describe clearly the stages, (b) states, (c) allowable decisions at each state in each stage, etc. Finally, please state what the optimal quantity of each product to be loaded to the plane is.
Problem 2
Suppose (by some miracle) that you have access to a particular company's stock prices over the next 10 days, and they are as follows:
Day Price
1
7
2
3
3
2
4
8
5
11
6
9
7
5
8
10
9
6
10
4It is the start of Day 1, and you do not own any shares. At the start of each day, you can either purchase one share or sell any shares that you have on hand (as many as you like, but not more than you own), or do nothing. Suppose that shares are worthless after Day 10 (the company goes bankrupt on Day 11). Your goal is to maximize profit over the 10-day period.
Please solve the above problem by formulating a dynamic program following the steps below
a)  What are the states and stages associated with this problem?
b)  What is the set of feasible actions associated with stage n and state s? How much is gained/lost by taking each action?
(Hint: It may be easier to let your action be the number of shares you have at the end of day n, rather than the number of shares you buy or sell on that day)
c)   How can the optimization function be interpreted here? That is, given a stage n and a state s, what is fn* (s)?
d)  Formulate the above problem as a dynamic program and solve it using GAMS/Python. Write the optimal sequence of actions below, and the profit that these yields.
Problem 3[Note: This is a bonus problem and not required – those students may work on it to earn an extra credit of at most 2 points that will be used to offset any possible loss of points from other problems, which are worth 10 points in total.]A government space agency is conducting a research project on an engineering problem that must be 代 写Computational Optimization Assignment #3Python
代做程序编程语言solved before people can safely fly to Mars. Three independent research teams are currently trying three different approaches to solve this problem.The probability that team 1 will fail to solve this problem is 0.40, the probability that team 2 will fail is 0.60, and the probability that team 3 will fail is 0.80. We say that the project fails if all three teams fail. So, currently, the probability that the project fails is 0.40 . 0.60 . 0.80 = 0.192.The space agency has decided to assign a total of three new scientists to the project. The three new scientists can be assigned together or separately to any of the teams. The following table gives the new probabilities of failure if 0, 1, 2, or 3 new scientists are assigned to each team. Our task is to use a dynamic programming approach to decide how many new scientists to assign to each team such that the probability of project failure is minimized.Number of new scientists                                                           Probability of failure
Team 1                                  Team 2                       Team 3
0                                                          0.40                                      0.60                            0.80
1                                                          0.20                                      0.40                            0.50
2                                                          0.15                                      0.20                            0.30
3                                                          0.10                                      0.17                            0.25
a)   What are the stages?
b)  What state information is needed to capture the essential information at the end of each stage?
c)   What are the options possible for each state in each stage?
d)  Give an word-description of the optimization function f *  to be computed for each state at each stage.
e)   Give a recurrence relation that gives a mathematical expression to compute the function f *
f)   Introduce the boundary conditions that allow you to start the computation of values off * .
g)  To what state and stage does f *  correspond to the optimal value of the overall problem?
h)  Carry out the computation by hand or using GAMS/Python to determine first the optimal value, and then the optimal solution for the data above. (If by hand, show some of your computation.  If using software, include all your source code and output.)



         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
