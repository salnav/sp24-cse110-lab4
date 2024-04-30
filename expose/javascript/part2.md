1. At line 12, 3 will be printed because the var keyword allows i to be accessed outside the for loop block, so the loop iterates until i is at the size of the array (3) and then it can be printed outside the for loop.
2. At line 13, 150 is printed. This is because the var keyword allows the discountedPrice variable to be accessed outside of the block it was declared at (the for loop), and it is set to 150 on the last iteration of the loop (300 * (1- 0.5)), and then able to be accessed and printed at line 13 (because of the var keyword).
3. At line 14, 150 is printed. On the last iteration of the loop finalPrice is set to 150. Since, finalPrice uses the var keyword it can be accessed anywhere in the scope of the function, and they are in the same scope, so after it is set to 150, it can be printed and accessed with no errors.
4. The function will return the array [50, 100, 150] which are the correct discounted prices. The finalPrice variable is declared with the var keyword, so it can be reassigned inside the loop with the discountedPrice and then added to the discounted array, so with these variable declarations the code works as it is intended to.
5. Line 12 will cause an error because since i is declared with the let keyword in the for loop, so it can only be accessed within the block it was defined in which is the for loop. Since, console.log(i) is called outside the block (for loop), it does not have access to i which is why there is an error.
6. Line 13 will cause an error because discountedPrice is declared with the let keyword, so it has a block scope. This means it can only be accessed inside of the block it was defined in which is the for loop. Console.log(discountedPrice) is outside of the block (for loop), so it causes an error.
7. Line 14 will print 150. This is because the finalPrice is defined with the let keyword, but it is in the same block as the console.log, so console.log has access to it.
8. The function will return the array [50, 100, 150] which are the correct discounted prices. Since none of the variables are used out of scope it works as intended.
9. Line 11 will cause an error because since i is declared with the let keyword in the for loop, so it can only be accessed within the block it was defined in which is the for loop. Since, console.log(i) is called outside the block (for loop), it does not have access to i which is why there is an error.
10. Line 12 will print 3. This is because the length of the prices array that is passed in is 3 and length is set to prices.length with the const keyword on line 4.
11. The function will return the array [50, 100, 150] which are the correct discounted prices. The discountedPrice is computed by declaring the variable with the const keyword and assigning the price in the array with a discount and this is done at each index in the array and added to the discounted array. Since, discounted is defined with the const keyword and an empty array, we can still push to the array because we are not reassigning a new array to it, but just adding to it. We return discounted with the correct values.
12. A. student.name
    B. student['Grad Year']
    C. student.greeting()
    D. student['Favorite Teacher'].name
    E. student.courseLoad[0]
13. Arithmetic
    A. The output is '32' because the integer 2 maps to its string representation '2' and the '3' and '2' string are concatenated.
    B. The output is 1 because the string '3' maps to its integer representation 3 and then subtraction is done with 3 - 2 = 1.
    C. The output is 3 because null just maps to 0, so it is 3 + 0 = 3.
    D. The output is '3null' because null maps to its string representation 'null' and the two strings are concatenated.
    E. The output is 4 because true maps to its integer representation 1 and then 1 + 3 = 4.
    F. The output is 0, since false and null both map to their integer representation which is 0, so 0 + 0 = 0.
    G. The output is '3undefined' because undefined maps to its string representation 'undefined' and the two strings are concatenated.
    H. The output is NaN because we cannot subtract with undefined.
14. Comparison
    A. The output is true because the string '2' maps to an integer and then the two integers are compared.
    B. The output is false because the two strings are compared lexicographically asnd '2' < '12' lexicographically.
    C. The output is true because '2' maps to an integer and then the two integers 2 and 2 are compared and 2 == 2. Since, the loose equality operator is used (==) the '2' converts to an integer.
    D. The output is false because the strict equality operator is used and both of the values are different types, so no conversions are made and it returns false.
    E. The output is false because true is converted to a 1 because loose equality is used and then 1 != 2, so false is returned.
    F. Boolean(2) returns true and since both values are the same type and the same value with the strict equality it is true.
15. The == is the loose equality, so it will do type conversions and compare if the two values are equal after. The === is the strict equality, so it will not do type conversions and will just return false if the two values are different types.
16. 21
    45
    5
    2
17. The result will be the modifyArray function returning [2, 4, 6] this is because the function passed in for callback is doSomething which takes in a number and multiplies it by 2. We loop through the array passed in and pass each value into the callback which is doSomething and add it to the newArray which is then returned.
19. 1
    4
    3
    2
