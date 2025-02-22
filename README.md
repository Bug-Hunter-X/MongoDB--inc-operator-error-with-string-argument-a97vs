# MongoDB $inc Operator Error with String Argument
This repository demonstrates a common error when using the `$inc` operator in MongoDB update queries. The error arises from providing a string argument to `$inc` instead of a number. This results in unexpected behavior, preventing the correct increment of the field.

## Bug
The original code uses the `$inc` operator with a string argument ('1') instead of a numeric argument (1). This leads to the `count` field not being incremented as intended.

## Solution
The solution involves correcting the argument type to ensure the `$inc` operator receives a numeric value. The corrected code uses the number 1 as the argument to correctly increment the `count` field.
