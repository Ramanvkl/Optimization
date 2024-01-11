# Overview

This repository includes sample optimization works using Linear Programming, Mixed Integer Programming, Non-Linear Programming, and an implementation of the Gradient Descent algorithm.

Problems in different contexts from supply chain to finance are explored in the notebooks. Here is a brief review of what can be found in each notebook:


## Linear Programming

This notebook explores various optimization cases in the context of supply chain management.

At the beginning, optimization of a balanced supply network is done. It is starting with optimizing the transporation of goods from 8 supply centers to 10 demand markets with the aim of minimizing the transporation costs. 

To get closer to the real world circumstances, a disruption in the supply network is then analyzed; 1 of the supply centers is shut down, which will make it an unbalanced supply network. Different questions rooted in real world scenarios are explored in this situation, where the supply chain is unbalanced.

Due to the nature of the problem, Linear Programming is utilized to solve all the problems in this notebook.


## Mixed Integer Programming

Problems solved in this notebook cannot be solved using Linear Programming since there are constraints to make the variables used in modeling the problems integer in real life. 

The notebook will start with an effort to optimize the allocation of the seats to the respresentatives of hypothetical provinces. Since we cannot have half-respresentatives or half-seats in real world, Mixed Integer Programming is utilized to find the fairest allocation with two different approaches. 

Next, we try to help a manager optimally allocate financial awards among a team's member such that maximizes the effectiveness of the rewards. There are also some business requirements addressed through constraints in this case, such as not having very low or high impact on too many of the team members.

Then, we will move back to our supply chain network from the Linear Programming notebook. This time we try to model the find the optimal strategy as a result of a competitor's actions within the context of an unbalanced supply network. Finally, we try to come up with crisis planning for future events. To do so, we find the best- and worst-case scenario that a disruption in the supply network can happen to the company and find the optimal allocation under these circumstances.


## Non-Linear Programming

Linearization is a powerful technique enabling us to simplify and solve many problems more efficiently, but it is sometimes not possible to Linearize the problem at hand. Therefore, this notebook explores two cases of non-linear programming.

First, we try to find the optimal allocation of a limited fund to a certain number of stocks with the aim of minimizing the portfolio risk. The problem is solved under two scenarios; first, we assume we are starting to invest meaning that there is no initial allocation. Then, we make it closer to the real life setting by assuming the fund is allocated and we are trying to minimize its risk. It is worth mentioning that in this case we consider transaction costs.

Lastly, the allocation of financial resources within an R&D department is studies. This case is analyzed twice; once with the aim of minimizing the total risk of the projects and another time wih the aim of maximizing the total profit.


## Gradient Descent

Gradient Descent is a powerful optimization algorithm with numerous applications. In this notebook, the algorithm is implemented with different learning rates and different objective functions, which clearly shows one case does not fit all. 
