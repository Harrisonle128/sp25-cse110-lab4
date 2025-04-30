1. Line 12 will print 3 because "i" was declared using var which is function scoped so it can still
be accessed outside the for loop. i is also incremented until 3 in the for loop. 
2. Line 13 would print 150 because the loop runs 3 times and ends at (300 *(1-0.5)) = 150. Like question 1,
"discounted price" is declared with var which is function scoped so it is accessed outside the for loop 
and holds the last value in the last iteration of the loop. 
3. Line 14 prints 150 because finalPrice is declared with var in the outer function scope, so it is accessible outside the loop and holds the last value price of 300.
4. The function returns [50, 100, 150] because it calculates the discounted price for each item and pushes the rounded value into the discounted array.
5. Line 12 will throw a reference error because "i" was declared using "let" which is block scoped so it is not 
accessible outside of the for loop. So it is not defined at discountPrices. 
6. Line 13 causes a ReferenceError because "discountedPrice" was declared using "let" inside the for-loop block and is not accessible outside of that block.
7. Line 14 prints 150 because "finalPrice" was declared with "let" in the outer function scope, so it remains accessible after the loop and holds the last value of the loop.
8. This function would return [50, 100, 150], but the code isn't displaying it (using consol.log(...)). For each price in the input array, it calculates the discounted value, rounds it to two decimal places, and stores it in an array then returns it. However
9. Line 11 causes a ReferenceError because "i" was declared using "let" inside the for loop, which is block-scoped. Therefore, it is not accessible outside the loop.
10. Line 12 prints 3. The variable "length" is declared with "const" in the outer function scope and holds "prices.length", which is 3.
11. This function returns [50, 100, 150]. It calculates the 50% discounted price for each value in the array, stores them in the "discounted" array, and returns it. 
    
12a. student.name
12b. student["Grad Year"]
12c. student.greeting()
12d. student.["Favorite Teacher"].name
12e. student.courseLoad[0]

13a."32" because 3 is a string and 2 is a number so it is just a string concatenation.
13b. 1 because 3 is a string but the minus is numeric which makes 3-2 = 1. 
13c. 3 because 3 + null is 3 where null is basically a 0. 
13d. "3null" because 3 is a string and when adding to null, null also becomes a string so it's a concatenation.  
13e. 4 because true just becomes a 1 so it's addition. 
13f. 0 because false is 0 and null is 0 so 0 + 0 = 0.
13g. "3undefined" because String concatenation with "3" and undefined becomes a string. 
13h. NaN because subtraction makes 3 become a number and undefined is NaN. 

14a. True because "2" becomes a number and 2 is greater than 1. 
14b. False because they are compared lexicographically. 
14c. True because the types become converted due to a loose equality. 
14d. False because it is a strict equality and they are different types. 
14e. False because true becomes 1 which is not equal to 2. 
14f. True because both are booleans. 

15. == performs type coercion if necessary before comparing whereas === checks both type and 
value without coercion. For example, 2 == "2" is true, but 2 === "2" is false. 

17.  The function returns [2, 4, 6]. Each element in the array [1, 2, 3] is passed to the callback function "doSomething", which multiplies the number by 2 which is then stored in a new array and returned.

19.The output will be: 1 4 3 2
JavaScript first executes console.log code (1 and 4), then handles the "setTimeout(..., 0)" which prints 3, followed by the delayed "setTimeout" that prints 2.






