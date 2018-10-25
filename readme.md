Implementation in Python

Given below is an example implementation of a genetic algorithm in Python. 

The y=target is to maximize this equation ASAP:
    y = w1x1+w2x2+w3x3+w4x4+w5x5+6wx6
    where (x1,x2,x3,x4,x5,x6)=(4,-2,3.5,5,-11,-4.7)
    What are the best values for the 6 weights w1 to w6?
    The genetic algorithm will be used for the best possible values after a number of generations.

This genetic algorithm tries to maximize the fitness function to provide a population consisting of the fittest individual 

In this example, after crossover and mutation, the least fit individual is replaced from the new fittest offspring.
