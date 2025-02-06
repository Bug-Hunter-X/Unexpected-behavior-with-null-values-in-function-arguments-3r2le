# JavaScript Bug: Unexpected Null Handling

This repository demonstrates a common JavaScript bug related to unexpected behavior when null values are passed as function arguments.

## Bug Description

The `foo` function in `bug.js` does not handle null values gracefully. When null is passed as `a` or `b`, the function might produce unintended results or even throw errors, depending on the implementation of the rest of the function.  This bug highlights the importance of explicit null checks and robust error handling.

## Solution

The `bugSolution.js` file provides a corrected version of the function, demonstrating proper null handling.

## How to Reproduce

1. Clone this repository.
2. Open `bug.js` and examine the buggy function.
3. Run the code with null arguments to observe the unexpected behavior.
4. Compare to `bugSolution.js` to see the correct implementation.

## Lessons Learned

This simple example illustrates the importance of always accounting for edge cases like null or undefined values when writing JavaScript functions.