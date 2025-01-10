# Unhandled Zero Division in TypeScript Arithmetic Functions

This repository demonstrates a common error in TypeScript: forgetting to handle edge cases, specifically division by zero. The `bug.ts` file contains functions for basic arithmetic operations. The `divide` function throws an error if the denominator is zero, but the example usage attempts to divide by zero.  This leads to a runtime error.

The `bugSolution.ts` file provides a corrected version with improved error handling and input validation.