# CMPS 2200 Assignment 3
## Answers

**Name:** Shania Phillips 


Place all written answers from `assignment-03.md` here for easier grading.

1a) 
def greedy_algorithm(N, Coin, k)
coin_num = 0
i = k
While N > 0:
  if N >= Coin[i]:
    N = N - Coin[i]
    coin_num++
  else:
    i = i - 1
return coin_num

1b) The algorithm gives the optimal time of O(k + N/2^k)

1c) W = O(k + N/2^k)
    S = O(log N)

2a) A counterexample could be the greedy algoritm might choose 2 nickels and a dime to make 20 when the optimal solution would be to use 2 dimes.

2b) The optimal substructure property is that there is an optimal solution to the subproblems within the optimal solution to the problem. 

2c) W = O(k * N)
    S = O(N)




