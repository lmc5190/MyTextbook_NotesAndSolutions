# Chapter 1 Exercises

## Exercise 1.1
**Give example of iterative learning from field of reinforcement learning.**
*Model*
Q-learning is the only algorithm needed to build a customer service agent for a car repair service.
*Deduction*
I hypothesize that applying q-learning to using data from previous customer service agents will produce a performant customer service agent.
*Data*
I reviewed scientific literature, and found that applying on q-learning will yield a customer service agent that is not performant in a production scenario.
By exploring beyound the boundaries of humans, like  telling a customer that they are crazy, the q-learning trained agent
will likely irritate customers.
*Induction*
Q-learning would not be a good fit for building a customer service agent. In similar cases, researchers have modified algorithms to make them
applicable to new use cases. I remember seeing a paper for deep q-learning from demonstrations. 
*Model*
Using deep q-learning from demonstrations is the algorithm needed to build a customer service agent for a car repair service.
*Deduction*
I hypothesize that applying deep q-learning from demonstration to previous data on customer service agents will produce a performant customer service agent.
I decide to read the paper on deep q-learning and gather previous demonstration data for a customer service agent.
*Data*
After reading the paper, I found that deep q-learning from demonstrations only works well when I have 50,000 demonstrations. However, the data I gathered only
has 100s of demontrations, and the paper shows that the algorithm is not performant in this regime.
*Induction*
DQfD would not be a good fit for building a performant customer service agent. Perhaps modifying deep q-learning from demonstrations will yield an algorithm 
that performs well with only 100s of data points. One would have to understand how the characteristic behaviors of the algorthm to know which
behaviors need to be addressed to make DQfD more efficient.
*Model*
One must learn the charteristic behaviors of DQfD in order to understand how it may be modified to yield better performance with a smaller
amount of training data.
*Deduction*
I hypothesize that by measuring key metrics, like average update size and time to task completion, over the application of DQfD on a 
simulatied environment, nearly as complex as a customer service environment, we can uncover characteristic behaviors and attempt to vary these
behaviors by tweaking the algorithm, so that it becomes more sample efficient.
