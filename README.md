# libmep

# Multi Expression Programming library

Implements the Multi Expression Programming (MEP) technique for solving regression and binary classification problems. MEP is a Genetic Programming (GP) variant with linear representation of chromosomes.

MEP introduced a unique feature: the ability to encode multiple solutions in the same chromosome. This means that we can explore much more from the search space compared to other techniques which encode a single solution in the chromosome. In most cases this advantage comes with no penalty regarding the running time or the involved resources.

C++ 11 is required due to the use of C++ 11 threads.

# To compile: 

Create a new project and add all files from "src" and one file from "tests" folder (which contains the main function). Include paths must point to the "include" folder of this project.

# Documentation

https://github.com/mepx/libmep/wiki

#More info:

http://www.mep.cs.ubbcluj.ro

#Discussion Group:

https://groups.google.com/d/forum/mepx

#Contact author:

mihai.oltean@gmail.com
