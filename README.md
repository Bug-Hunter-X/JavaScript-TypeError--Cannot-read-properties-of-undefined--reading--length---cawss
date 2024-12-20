# JavaScript TypeError: Cannot read properties of undefined (reading 'length')

This repository demonstrates a common JavaScript error and its solution. The error occurs when attempting to access the 'length' property of an undefined variable.  The provided code shows the bug and a robust solution.

## Bug

The original code throws a `TypeError` when the input 'a' is undefined. This is because the code attempts to access the 'length' property of an undefined value which results in the error.

## Solution

The solution adds a check for both `null` and `undefined` values.  This ensures that the code handles both cases gracefully, preventing the `TypeError` and returning a consistent result.  It's important to explicitly check for `undefined` in JavaScript to handle such edge cases reliably.
