# MongoDB $inc Operator Error
This repository demonstrates a common error when using the `$inc` operator in MongoDB update queries.  The `$inc` operator is used to increment a numeric field by a specified value. However, providing a string value instead of a number will result in an unexpected outcome or error.

## Bug Description
The bug occurs when attempting to increment a field with a string value using the `$inc` operator. MongoDB expects a numeric value for increment operations.  This leads to the update operation failing or producing unexpected results.

## Solution
The solution involves ensuring that the value provided to `$inc` is a number, not a string.  Correcting the data type will resolve the issue and allow the intended increment operation to execute successfully.
