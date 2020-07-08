# Non dominated Sorting Genetic Algorithm II Tutorial

This notebook aims to help the reader understand how the NSGA-II algorithm works, and how to implement it. \
NSGA-II was introduced in the paper: \
A Fast and Elitist Multiobjective Genetic Algorithm: NSGA-II  \
Kalyanmoy Deb, Associate Member, IEEE, Amrit Pratap, Sameer Agarwal, and T. Meyarivan

This tutorial assumes familiarity with genetic algorithms, but no prior knowladge on multi objective optimization

Contents:
- Concepts: Domination, Multi objective optimization, Pareto front
- A real world example: Starcraft build orders
- A simple example
- Brute force solution
- Non dominated sorting: naive approach (worst case complexity O(M N^3))
- Non dominated sorting: fast approach (worst case complexity O(M N^2) )
- Diversity Preservation
- Putting it all togeather
- Solving the toy problem
- Solving a more complex problem
