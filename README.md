# JavaScript Closure Issue in setTimeout Loop

This repository demonstrates a common closure-related bug in JavaScript when using `setTimeout` within a loop.  The incorrect code leads to all callbacks logging the final value of `i` (10) instead of the expected values 0 through 9.

The solution demonstrates a proper way to handle this using closures by creating a self-executing function to capture the value of `i` in each iteration.