# Haskell Sort Function Misunderstanding

This example demonstrates a common misconception when using the `sort` function in Haskell.  Many programmers from imperative backgrounds expect `sort` to modify the original list in place. However, Haskell is purely functional; `sort` creates a *new* sorted list, leaving the original list unchanged.

The included `bug.hs` file shows the incorrect expectation, and `bugSolution.hs` demonstrates the correct way to handle sorting in Haskell.
