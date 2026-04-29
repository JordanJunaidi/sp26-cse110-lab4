1. Line 9 prints the sum of `num1` and `num2`, which is stored in the variable `result`
2. Line 13 also prints the sum of `num1` and `num2`, which is stored in the variable `result`
3. Var can easily lead to issues because of how it doesn't follow block scoping and also because of
  how it can cause naming issues or redeclaration issues. This makes it harder to debug and
   pinpoint issues when they come up.
4. Line 9 prints the sum of `num1` and `num2`, which is stored in the variable `result`
5. Line 13 causes an error. Since we are using the `let` keyword this time, the `result` variable is only available within the scope of the if statement. Since line 13 is outside of the if statement block
  and attempts to access the `result` variable, it throws an error.
6. Nothing is printed on Line 9 because the code returns an error when it attempts to reassign
  `result`. This is because `result` was declared using the `const` keyword, so it cannot be reassigned, and
   thus the code crashes and returns an error.
7. Nothing is printed on Line 13 for the same reasons that nothing is printed on Line 9.

