# Incorrect use of $inc operator in MongoDB update

This example demonstrates an incorrect usage of the `$inc` operator in a MongoDB update operation.
The `$inc` operator is used to increment a numerical field by a specified value. However, if a string value is used instead of a number, an error or unexpected behavior will occur.

## Bug
The provided code snippet shows an incorrect usage of the `$inc` operator. The value being incremented is a string instead of a number which could potentially lead to errors during the update operation.

## Solution
The solution involves providing the correct numerical value to the `$inc` operator.
