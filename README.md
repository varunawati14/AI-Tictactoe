# AI-Tictactoe

A game of Tic Tac Toe using heuristics.


Minimax is a backtracking algorithm that is used to find the optimal move for each position, assuming that the opponent plays optimally.

Essentially we are finding the most optimal path based off a given end result.

In the above example, the first turn attempts to maximize, whereas the turn after that is minimizing. Looking at each possible case and performing some pruning, we can figure out the best path to take.

The first move is trying to maximize, so it would pick Left, because it assumes that the opponent will play optimally. The next move is trying to minimize, so it would pick 3, leaving us with the optimal path.

This is generalized to tictactoe, where each parent has a lot more branches for each of the possible moves.
