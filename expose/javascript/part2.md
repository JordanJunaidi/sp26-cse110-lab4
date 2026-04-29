1. Line 12 will print out `3`. This is because the variable `i` is declared using the `var`
   keyword, so it has function scope. In the for loop, `i` gets incremented by 1 until `i<prices.length`,
   where `prices.length=3`. So when the loop terminates, `i=3`, which is why Line 12 prints out `3`.

2. Line 13 will print out `150`. This is because the variable `discountedPrice` is declared using the `var` keyword in the for loop, so it has function scope. In the last iteration of the loop before it terminates,
   `discountedPrice=150`, so once the loop is over and we print out `discountedPrice`, we get that value
   of `150`.

3. Line 14 will print out `150`. After the last iteration of the foor loop, `finalPrice=150`, so line 14 prints out `150`.

4. The function will return `[50, 100, 150]`. The original prices are `[100, 200, 300]` and the discount is `0.5`. Following the logic in the for loop, each price gets cut in half and added to the `discounted` array, which is returned at the end of the function

5. Line 12 will cause an error because unlike before, `i` is being declared using the `let` keyword instead of the `var` keyword. This means that `i` is limited in scope to the for loop block. Thus, trying to print `i` outside of the for loop block will result in an error.

6. Line 13 will cause an error. Similar to the previous instance, `discountedPrice` was declared using the `let` keyword in the for loop block, so it is unable to be called / referenced outside of the block.

7. Line 14 will print out `150`. `finalPrice` was declared using the `let` keyword, but it was declared outside of the for loop, so it has function scope and is able to be printed without any errors.

8. The function will return `[50, 100, 150]`. The variables being declared using `let` does not affect the final result and the function still creates the `discounted` array as intended.

9. Line 11 will cause an error because `i` is declared using `let` in the for loop, so it cannot be printed outside of the for loop.

10. Line 12 will print out `3`. `length` is declared at the beginning of the function in the outermost block, so it is able to be accessed in line 12. The `prices` array has a length of 3, so `length=3`

11. The function returns `[50, 100, 150]`. The original prices are `[100, 200, 300]` and the discount is `0.5`, so the resulting discounted prices are `[50, 100, 150]`

12. A. `student.name`
    B. `student['Grad Year']`
    C. `student.greeting()`
    D. `student['Favorite Teacher'].name`
    E. `student.courseLoad[0]`
