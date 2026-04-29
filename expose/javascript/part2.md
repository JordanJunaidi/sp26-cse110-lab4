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

13. A. Output: `32`. The integer 2 maps to its exact string representation, resulting in the string '32'
    B. Output: `1`. The string `3` gets converted into the integer value 3
    C. Output: `3`. null gets represented as 0
    D. Output: `'3null'`. null gets represented by its string representation 'null'
    E. Output: `4`. true has a value of 1
    F. Output: `0`. false and null both have values of 0
    G. Output: `'3undefined'`. undefined gets representated by its string representation 'undefined'
    H. Output: `NaN`. undefined cannot be represented as a number, so substraction is not possible

14. A. Output: `true`. The integer value of 2 is greater than 1
    B. Output: `false`. '12' comes before '2' in alphabetical order, so the right inequality is `'2'>'12'`
    C. Output: `true`. The '2' gets converted into an integer, and 2 == 2.
    D. Output: `false`. The === operator also checks types, but 2 and '2' are not the same type so it is false
    E. Output: `false`. True has a value of 1, and 1 != 2.
    F. Output: `true`. Positive integers are considered true, and true == true is true.

15. The == operator checks values. If the types are mismatched, the operator will convert the types to make them match first. On the other hand, the === operator checks if 2 things are exactly the same, including their types.

16. Output: `[2, 4, 6]`. The input array starts as `[1, 2, 3]`. Then, `newArr` is initialized as an empty array. The for loop iterates through all the elements in the input array, and calls the `doSomething` function on each element. The `doSomething` function multiplies the value by 2. Then, the `modifyArray` function pushes the new value from `doSomething` into `newArr`, which is then returned at the end.

17. Output:

```
1
4
3
2
```

1 and 4 get printed as the code is run, then 3 after its timeout of 0, then 2 after the timeout of 1 second.
