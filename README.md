# MongoDB $inc Operator on String Field

This example demonstrates an incorrect use of the `$inc` operator in MongoDB. The `$inc` operator is used to increment a numeric field, but in this case, it is being applied to a string field, which results in an error.

## Bug
The `bug.js` file shows an incorrect implementation that attempts to increment a string field using `$inc`.

## Solution
The `bugSolution.js` file provides the correct solution that handles the increment operation appropriately.
