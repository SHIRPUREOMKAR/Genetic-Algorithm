# Genetic Algorithm for Optimization

This Python script implements a genetic algorithm to optimize a fitness function. In this case, the fitness function is defined as:

```python
def value(x, y, z):
    return 3*x**4 + 3*y**6 + 3*z - 679
```
It runs the algorithm for specified generations (here, 10000), and with a user given accuracy to find the best possible precise solutions for the any given equation
