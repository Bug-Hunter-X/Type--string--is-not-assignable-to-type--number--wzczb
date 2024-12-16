# Type 'string' is not assignable to type 'number' in TypeScript
This example demonstrates a common type error in TypeScript where a function expecting a number receives a string.  The error message, "Type 'string' is not assignable to type 'number'", indicates a type mismatch.

## Bug Description
The `add` and `subtract` functions are defined to accept two number arguments and return a number.  However, if string arguments are passed, a TypeScript compilation error will occur.  This is because TypeScript's type system enforces type safety.

## Solution
The solution involves ensuring that only numbers are passed to these functions.  Strict type checking is part of TypeScript's strength and helps prevent runtime errors.