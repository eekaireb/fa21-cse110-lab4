1. On line 12, the value of `i`, **3**, will be output to the console. This is because `i` was declared with var, so the variable still exists after the for-loop ends.
2. On line 13, the value of `discountedPrice`, **150**, will be output to the console. This is because `discountedPrice` was declared with keyword var, so it still exists once the for-loop ends. 
3. On line 14, the value of `finalPrice`, **150**, will be output to the console. This is because `finalPrice` was declared with the keyword var. But in this case even if we used the keyword let, `finalPrice` would still have been output to the console, since it is in the scope of the call to log on line 14. 
4. The function will return the value of the `discounted`, which is **[ 50, 100, 150]**. This is because `discounted` was created with the keyword var so we are able to modify it and it exists for the scope of the entire function (and continues to exist once the function ends). 
5. The code returns an error because `i` was declared with the keyword let, so it is local to the scope of the for-loop. Because of this, when we are trying to access `i` after the for-loop ends, `i` no longer exists and we get an error.
6. The code returns an error because `discountedPrice` was declared inside of the for-loop, and thus has the scope of only that block. We are trying to access `discountedPrice` outside of its scope on line 13.
7.  On line 14, the value of `finalPrice`, **150**, will be output to the console. This is because, though `finalPrice` was declared with the keyword let, it is in the scope of where we are trying to access it. 
8.  The function will return the value of the `discounted`, which is **[ 50, 100, 150]**. The function will return this becauase `discounted` was declared with let, so we are able to modify it (as we do in the for-loop). Additionally, `discounted` was declared in the same scope as the return statement. 
9.  The code returns an error because `i` was declared with the keyword let, so it is local to the scope of the for-loop. Because of this, when we are trying to access `i` after the for-loop ends, `i` no longer exists and we get an error.
10. On line 12, the value of `length`, **3**, will be output to the console. This is because we do not attempt to modify length anywhere (no issues with the const declaration), and `length` was declared in the scope that we are trying to access it in.
11. The function will return the value of `discounted`, which is **[ 50, 100, 150]**. This is because, though `discounted` was declared with const, we are not reassigned or redeclaring the variable, we are only adding to the list which does not cause any errors. Additionally `discounted ` was declared in the same scope as the return statement. 
12. 
    a. student.name
    b. student['Grad Year']
    c. student.greeting()
    d. student['Favorite Teacher']['name']
    e. student['courseLoad'][0]
13. 
    a. The output was '32'. This is because the integer 2 was mapped to its string representation and then the '3' and '2' were concatinated.

    b. The output was 1. This is because the '3' was mapped to its integer representation and then the computation 3-2=1 was performed.

    c. The output was 3. This is because the value null was mapped to the integer 0 and then the computation 3-0=3 was performed. 

    d. The output was '3null'. This is because the null value was mapped to the string 'null' and then '3' was concatinated with 'null'.

    e. The output was 4. This is because the boolean value true was mapped to an integer representation of 1. Then the computation 1+3=4 was performed.

    f. The output was 0. In this case, false was mapped to its integer representation of 0 and null was mapped to its integer representation of 0. Then the computation 0+0=0 was performed.

    g. The output was '3undefined'. This is because undefined was mapped to a string representation, 'undefined'. Then '3' was concatinated with 'undefined'.

    h. The output was NaN. This is because, while '3' could be mapped to the integer representation of 3, undefined is mapped to NaN. Performing a computation with NaN will return NaN.
14. 
    a. The output is true. This is because '2' is mapped to its integer representation of 2. Thus, 2 > 1 is true. 

    b. The output is false. Since both '2' and '12' are strings, the comparision is based on their lexicographical order. Lexicographically, '2' is greater than '1', thus '2' is the greater than '12'.

    c. The output is true. This is because '2' is mapped to its integer representation of 2. Thus the comparison is 2 == 2, which is true.

    d. The output is false. This is because === does not match the types of 2 and '2' before the comparison, thus 2 does not equal '2' as they are different types.

    e. The output is false. This is false because true is mapped to its integer representation which is 1, and 1 does not equal 2.

    f. The output is true. This is because Boolean(2) will return true and is clearly of type boolean. Thus both sides of the equality are the same type and have the same value.
    
15. The difference is that == will convert the variables to the same type before doing a comparison, while === will not perform type conversion and returns true only if the variables are the same type and value. 
16. See part2-question16.js
17. d
18. d
19. 
    
