# Knapsack problem
To solve Knapsack problem using Greedy method.

# ALGORITHM
The weights (Wi) and profit values (Pi) of the items to be added in the knapsack are 
taken as an input for the fractional knapsack algorithm and the subset of the items added 
in the knapsack without exceeding the limit and with maximum profit is achieved as the 
output.

• Consider all the items with their weights and profits mentioned 
respectively.

• Calculate Pi/Wi of all the items and sort the items in descending order 
based on their Pi/Wi values.

• Without exceeding the limit, add the items into the knapsack.

• If the knapsack can still store some weight, but the weights of other items 
exceed the limit, the fractional part of the next time can be added.

• Hence, giving it the name fractional knapsack problem.

# Time Complexity
O( N*LogN), where N is the number of items given.

# Space Compleity: 
O(N), where N is the number of items given.
