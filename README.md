# Hack Recursive Function Stack Overflow Example

This repository demonstrates a common error in Hack: stack overflow in recursive functions. The code includes two functions: `foo`, which calculates the factorial, and `bar`, which calculates the sum of numbers from 1 to x. Both functions use recursion. 

For large inputs, these functions will cause a stack overflow error because the call stack grows excessively deep. The solution demonstrates how to handle recursion in a way that prevents stack overflow. The solution uses iteration instead of recursion which is a better approach for these cases to avoid stack overflow.