# MongoDB $inc Operator Bug
This repository demonstrates a common error when using the `$inc` operator in MongoDB. The `$inc` operator is used to increment or decrement a numerical field by a specified value.  However, if the field does not exist or if the value is not a number, the behavior can be unexpected.

## Bug Description
The code in `bug.js` incorrectly uses the `$inc` operator, leading to unintended consequences when the field to increment does not exist or is not a number.

## Solution
The `bugSolution.js` file provides a corrected implementation, employing appropriate error handling and checks to mitigate the issue.