# Programming_Assignment_2
_Peer-graded Assignment: Programming Assignment 2: Lexical Scoping_

_Assignment: Caching the Inverse of a Matrixless_

Matrix inversion is usually a costly computation and there may be some benefit to caching the inverse of a matrix rather than compute it repeatedly (there are also alternatives to matrix inversion that we will not discuss here). Your assignment is to write a pair of functions that cache the inverse of a matrix.

# Write the following functions:

1. makeCacheMatrix: This function creates a special "matrix" object that can cache its inverse.
2. cacheSolve: This function computes the inverse of the special "matrix" returned by makeCacheMatrix above. If the inverse has already been calculated (and the matrix has not changed), then the cachesolve should retrieve the inverse from the cache.
# Computing the inverse of a square matrix can be done with the solve function in R. For example, if X is a square invertible matrix, then solve(X) returns its inverse.
