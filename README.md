# 2018_Summer_1CGM_Programs

## What do the programs do?
I coded these programs (C++) to find **1C-GM** or __1 Cycle Geometric Mean__ Graphs.


## What is a 1C-GM Graph?
### Key Terms
- Cycle
  - A closed path. (Think of any n-gons [pentagon,hexagon, ..., etc] composed of edges and vertices.)
- Geometric Mean
  - Value derived by taking the square root of the product of two numbers.

### Taken Altogether...
A 1CG-M Graph is a **cycle,** whose **edges** are derived from taking the **geometric mean** of the vertices. Below are examples of what this would look like. Many of the cycle graphs I worked with had chords connecting non-adjacent vertices together. In order for a cycle to be considered 1C-GM however, the **edges** must proceed {1,2,3...[total number of edges]) and the **vertices** must be non-consecutive numbers in the range **1 to q+1**.


## Research
I coded these programs are part of my research under Professor Emeritus Sin-min Lee (San Jose State University). These graphs belong to the sub-branch of pure mathematics graph theory, and are known as graph-labeling problems. As expected, working out the 1C-GM graphs out by hand is quite tedious so I coded **these** programs to do the gruntwork for us! The main algorithm (i/o) used is for all intents and purposes, bruteforce ... so as the complexity of the graphs proceed, the main program had difficulties efficiently sorting out the individual cases. As a result, I coded some sub-programs to solve specific cases for potential 1C-GM graph configurations. We are working on a research paper on our findings which will be submitted for review to be published in **Congressus Numerantium** by the end of November.
