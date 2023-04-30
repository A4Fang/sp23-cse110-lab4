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
12. Q12
    1.  student.name
    2.  student["Grad Year"]
    3.  student.greeting()
    4.  student["Favorite Teacher"].name
    5.  student.courseLoad[0]
13. Q13
    1. '3' + 2 = '32', the int: 2 is converted to a string and the operation combines the two strings.
    2. '3' - 2 = 1, the string: 3 is converted to an int and the oeprations follows as a math expression
    3. 3 + null = 3, null is the value 0.
    4. '3' + null = '3null', the null value is converted to the string 'null'
    5. true + 3 = 4, true's integer value is 1
    6. false + null = 0, both integer values are 0
    7. '3' + undefined = '3undefined', undefined is converted to the string 'undefined'
    8. '3' - undefined = NaN, undefined has a value NaN, which is not a number so a math operation with NaN will always be NaN.
 14.  Q14
      1.   '2' > 1: true, the string 2 becomes the int 2
      2.   '2' < '12': false, compares the string 2 and 12 in which the first character compared is 2 and 1 in which '2' > '1'
      3.   2 == '2': true, the string two becomes the int 2
      4.   2 === '2': false, doesn't type convert and the string '2' is different from int 2 
      5.   true == 2: false, true has an integer value 1
      6.   true === Boolean(2): true, the rule of Boolean conversion is any value that are intuitively "empty" (0, null, undefined, NaN) are false. Otherwise, true.
 15.  The difference between == and === is that putting an === does not convert the type of the variable while == does and compares it.
 16.  Refer to [this file](part2-question16.js)
 17.  
 



