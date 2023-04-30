# Part 2 Answers

1. Line 12 will print 3 because variables can be called from inside the function block. Since we gave the parameter an array of length 3, the variable will end at i=3 which tells the code to stop iterating the command. `console.log(i)` occurs inside the function block so the variable i can be called.
2. Line 13 will print 150 because we used discountedPrice as a variable to calculate the discounted price of each price in the prices array. The last thing we checked was for the price 300, in which discountedPrice stored the value 150 in which we did not change after that.
3. Line 14 will print 150 in the same manner as before since the last price checked 300, has a discount of 150 after rounding it to the nearest two decimals.
4. The function will return an array with the discounted prices in their respective index, but will not print anything because we did not tell the code to do so.
5. The function will throw a ReferenceError because the variable i is declared inside the "for" block and line 12 is attempting the call it outside the scope of i.
6. The function will also throw a ReferenceError because discountedPrice was declared inside the for block and the print statement is outside the scope.
7. The function will print 150 because finalPrice was declared inside the function block in which the print statement is also in and the value stored is explained in question 3.
8. The function will return the array of discounted prices, but prints nothing.
9. The function will throw a ReferenceError because i was declared in the for block but the print statement is called outside the scope of it.
10. Line 12 will print 3 because length was declared in the function block which is where the print statement is called as well. We stored the length of the array given in length which is 3 and did not attempt to change the value of length.
11. The function will still return the discounted array, once again print nothing.