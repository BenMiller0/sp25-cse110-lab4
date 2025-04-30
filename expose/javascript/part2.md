1. Line 12 prints `3` because the for loop iterates 3 times because the length of prices is 3. 
2. Line 13 prints `150` because `discountedPrice` uses the `var` keyword that gives it function scope and the last value given to it is 150.
3. Line 14 prints `150` because `finalPrice` uses the `var` keyword that gives it function scope and the last value given to it is 150.
4. The function will return `[ 50, 100, 150 ]` because it applies the discount to each input in the array. 
5. Using `let i` to declare `i` means it falls out of scope after the loop causing an error at line 12. 
6. This causes an error because using `let` for `discountedPrice` means it falls out of scope after the loop by line 13. 
7. Line 14 prints `150` as expected because it is in the same scope as when `finalPrice` was decalred on line 4. 
8. This returns `[ 50, 100, 150 ]` like before because there are no scopping issues if you comment out the log statements. 
9. Line 11 causes an error because `i` falls out of scope by line 11.
10. Line 12 prints 3 because `const length` makes the scope the entire block it was defined in which is within the print statement on line 12. 
11. This returns `[ 50, 100, 150 ]` because there are no variable scopping issues.
12. a. student.name b. student["Grad Year"] c. student.greeting() d. student["Favorite Teacher"].name e. student.courseLoad[0]
13. a. 32 b. 1 c. 3 d. '3null' e. 4 f. 0 g.'3undefined' h. Nan 
14. a. true b. false c. true d. false e. false f. true 
15. `==` Is loose equlity and will do type conversion to compare if nessesary while `===` compares type and value for eqaulity. 
16. Answer in `part2-question16.js`
17. The result will be `[2, 4, 6]`. The function `modifyArray` calls back to the `doSomething` function that multiplies all the array arguments by 2.
18. part2-question18.js
19. Ths code prints 1, 4, 3, 2. It prints the non-timeout code first and then the timeout functions in the order of how short their timeouts are.