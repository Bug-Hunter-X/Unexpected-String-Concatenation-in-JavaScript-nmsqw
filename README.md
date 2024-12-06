# Unexpected String Concatenation in JavaScript

This example demonstrates a common issue in JavaScript stemming from its dynamic typing.  When adding numbers and strings, JavaScript performs string concatenation instead of numerical addition unless explicitly handled.

## Bug:
The `foo` function intends to add two numbers, but it concatenates them because the second argument is a string.

## Solution:
Convert string arguments to numbers using `parseInt()` or `parseFloat()` before performing the addition to ensure numerical addition takes place.
