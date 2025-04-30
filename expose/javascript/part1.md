1. Line 9 prints `values added:  20`
2. Line 13 prints `final result:  20`
3. You shouldn't use var because it gives limited control over the variable scope. Variables declared with var are scoped to the whole function, not the block they're defined in. This can lead to unexpected behavior and increases the likelihood of bugs.
4. Line 9 prints `values added:  20`
5. Line 13 causes an error because `result` is not defined because it feel out of scope as the `let` keyword reduces the scope to just the block it was defined in. 
6. Line 9 causes an error because result was a `const` and you cannot change a `const`.
7. Line 13 also causes an error because result was a `const` and that makes its scope only within the block it was defined in and thus by line 13 is fell out of scope.