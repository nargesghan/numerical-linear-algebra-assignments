# numerical-linear-algebra-ssignments

# Jacobi method

In this code, we first import the libraries we need.

Then, we write a function that solves the system using the Jacobi method by taking the desired inputs.

Inputs:
1. The coefficient matrix of the system
2. The right-hand side of the equation in the form of a vector
3. Initial values of X
4. Number of iterations

First, we check that the values on the diagonal of A are not 0. Then, to avoid division by zero, we convert it to the desired state by swapping rows and columns. (Global and partial alignment)

It should be noted that the inputs are all strings. So, in each neighborhood, we convert the inputs to the desired matrix using array(ast.literal_eval(A)).

<strong>Jacobi algorithm:</strong>
![image](https://github.com/nargesghan/numerical-linear-algebra-ssignments/assets/72782438/0f2311d6-b989-4462-8ce1-64efd5c4e1a4)

<strong>Note:</strong>
Matrix R is the same as L+U.

<strong>refreces:</strong>
https://www.quantstart.com/articles/Jacobi-Method-in-Python-and-NumPy/
