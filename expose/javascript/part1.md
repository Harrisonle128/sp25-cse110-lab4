1. Line 9 would print: values added: 20
2. Line 13 would print: final result: 20
3. Var shouldn't be used because it is not blocked scoped and rather function scoped which could 
lead to bugs where the variable leaks as we just saw in line 13 returning 20. It is accessible
in places in the code that it shouldn't be.
4. Line 9 would print: values added: 20
5. Line 13 returns a reference error because result was declared using 'let` inside the if block, 
so it cannot be accessed outside of that block.
1. Line 9 doesn't print and is never reached because an error is thrown in line 7 because of the assignment to result
which is a constant variable. You can't do that. 
2. Line 13 also doesn't print and is never reached because of the same error 