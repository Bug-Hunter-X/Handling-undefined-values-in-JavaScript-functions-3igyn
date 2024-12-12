# Handling undefined values in JavaScript functions
This repository demonstrates a common error in JavaScript where functions may not handle undefined values correctly.  The `bug.js` file shows the buggy code, while `bugSolution.js` provides a corrected version.

The problem arises when the function `foo` receives `undefined` as input.  The original code attempts to access the `length` property of `undefined`, resulting in a `TypeError`. The solution involves adding a check for `undefined` to gracefully handle this situation.