# MongoDB $inc Operator Error

This repository demonstrates a common error when using the `$inc` operator in MongoDB. The `$inc` operator is used to increment a numeric field by a specified value. However, if the value provided is not a number, MongoDB will throw an error.  This example shows the incorrect usage of the operator and a corrected version.

## Bug
The `bug.js` file shows an incorrect usage of the `$inc` operator. The value being incremented is a string instead of a number, which leads to an error.

## Solution
The `bugSolution.js` file demonstrates the correct usage of the `$inc` operator with a numeric value to increment the field.
