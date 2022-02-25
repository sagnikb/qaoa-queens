# N Queens via QAOA

## Introduction

The Quantum Approximate Optimization Algorithm (QAOA) is an appealing candidate for solving combinatorial optimization problems on a quantum computer. Here we apply QAOA to a particular integer programming problem called the generalized exact cover problem. We first talk about the exact cover problem, then the generalized exact cover problem, and show how to reduce the generalized problem to the exact problem. Later, we show how to use QAOA to find a solution to the exact cover problem. Throughout, we use the $N$-queen problem as a running example. This well known problem asks the following question - how to place $N$ queens on an $N \times N$ chessboard such that none of the queens attack eachother?