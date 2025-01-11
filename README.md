# CSS `calc()` function overrides `min-width` unexpectedly

This repository demonstrates an uncommon bug in CSS related to the interaction between the `calc()` function, percentages, and the `min-width` property.

## Bug Description

The `calc()` function in CSS is used to perform calculations within CSS property values. However, when combining `calc()` with percentages and a `min-width` declaration, unexpected behavior can occur.  If the result of the `calc()` expression is less than the `min-width`, the `min-width` is sometimes ignored.

## How to Reproduce

1. Clone this repository.
2. Open `bug.css` and `bugSolution.css`.
3. Observe the different behavior between the buggy code and the solution.