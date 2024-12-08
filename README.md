# Infinite Loop Bug in JavaScript While Loop

This repository demonstrates a common error in JavaScript: an infinite loop caused by a missing increment in a `while` loop. 

## Bug Description

The `bug.js` file contains a `while` loop that is supposed to iterate 10 times. However, due to the missing increment of the loop counter variable `i`, the loop condition `i < 10` will always be true. This results in an infinite loop that never terminates.

## Solution

The `bugSolution.js` file provides the corrected code. The issue is resolved by adding the increment `i++` within the loop body. This ensures that the loop counter is updated in each iteration, allowing the loop to terminate correctly.

## How to Reproduce

1. Clone the repository.
2. Open `bug.js` and run it in a JavaScript environment (e.g., browser's console or Node.js).
3. Observe the infinite loop. 
4. Open `bugSolution.js` and run it to see the corrected behavior. 
