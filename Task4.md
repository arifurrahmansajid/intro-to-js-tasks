### Task-4

What will be the result of the following codes:

**var a = isNaN(‘11’);**

**var a = isNaN(2-10);**

Explain your answers.

1st Code:
javascript
Copy
Edit
var a = isNaN('11');
Explanation:

The isNaN() function checks whether a value is Not a Number (NaN).
The string '11' is a numeric string.
JavaScript automatically converts numeric strings to numbers when evaluating isNaN().
'11' is converted to 11, which is a valid number.
Therefore, isNaN(11) returns false.
Result:
a = false

2nd Code:
javascript
Copy
Edit
var a = isNaN(2 - 10);
Explanation:

The expression 2 - 10 evaluates to -8.
-8 is a valid number.
isNaN(-8) returns false since -8 is not NaN.
Result:
a = false

Final Answer:
isNaN('11') → false (since '11' is converted to a number).
isNaN(2 - 10) → false (since -8 is a number