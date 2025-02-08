# MongoDB $inc Operator Error with String Increment

This example demonstrates a common error when using the `$inc` operator in MongoDB update operations.  The `$inc` operator is designed to increment numerical fields.  Attempting to increment a field with a string value will lead to an error or unexpected behavior.

The `bug.js` file contains the code with the error, while `bugSolution.js` provides the corrected version.
