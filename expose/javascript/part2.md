1. Line 12 prints `3` because the for loop iterates 3 times because the length of prices is 3. 
2. Line 13 prints `150` because `discountedPrice` uses the `var` keyword that gives it function scope and the last value given to it is 150.
3. Line 14 prints `150` because `finalPrice` uses the `var` keyword that gives it function scope and the last value given to it is 150.
4. The function will return `[ 50, 100, 150 ]` because it applies the discount to each input in the array. 
5. Using `let i` to declare `i` means it falls out of scope after the loop causing an error at line 12. 
6. This causes an error because using `let` for `discountedPrice` means it falls out of scope after the loop by line 13. 
7. Line 14 prints `150` as expected because it is in the same scope as when `finalPrice` was decalred on line 4. 