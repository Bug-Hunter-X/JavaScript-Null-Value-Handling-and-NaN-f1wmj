# JavaScript Null Value Handling and NaN

This repository demonstrates a common JavaScript bug related to the handling of null values and the resulting NaN (Not a Number) values.

## The Bug
The `bar` function implicitly attempts to perform arithmetic on null values, which results in NaN. The `foo` function explicitly checks for null values and handles them gracefully.

## The Solution
Explicitly checking for and handling null values (and potentially other unexpected values) prevents unexpected NaN results.

## How to Reproduce
1. Clone this repository.
2. Open the `bug.js` file.
3. Run the code using a JavaScript interpreter (e.g., Node.js).