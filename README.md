# JavaScript Hoisting Bug

This repository demonstrates a common issue in JavaScript related to hoisting.  The code in `bug.js` shows how variables declared with `var` are hoisted, but not initialized to their declared values.

The solution in `bugSolution.js` shows how using `let` or `const` can prevent this issue.  `let` and `const` are not hoisted in the same way as `var`, leading to more predictable behavior.
