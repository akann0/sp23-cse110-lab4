** Answers to Part 1 **

1. Line 12 will print the value of 3.
i is a var and therefore has function scope, so it is still
valid to call i outside of its original block.
i will have the first value that fails (i < prices.length),
which is 3

3. Line 13 will print the last value of discounted
which is 150.00.

discountedPrice has functionscope and 
line 13 is within the function 
scope of the variable declaration.

var discountedPrice is a non-issue because the var type allows 
for redeclaration.


3. Line 14 will print the last value of finalPrice
which is 150.00.

finalprice has functionscope and line 14 is within the function 
scope of the variable declaration.

var discountedPrice is a non-issue because the var type allows 
for redeclaration.

4. This function is a valid function and will return
half of the original prices array, which is 
[50, 100, 150].

5. This function will throw an error as i is called outside of 
scope.

6. This will not work the same way as before as 
discounedPrice is called outside of scope in line 13.

Therefore, this will cause an error

7. This function will behave the same way as before, 
and therefore the last value of finalprice which is 150.00
will be printed to terminal.

8. This function will behave the same way as number 4 
and therefore [50, 100, 150] will be returned.

9. i is referenced outside of scope and therefore an error
occurs.

10. this code works as before  (const variables can still be 
manipulated).  Thererfore, at line 12 the number 3
will be printed.

11. This function will behave as designed and therefore 
[50, 100, 150] will be returned

12. 
student.name;
student.major;
student.greeting();
student["Favorite Teacher"].name;
student.courseLoad[0];

13. 
a) 32, as 2 is converted to a string before the concatenate
function
b) 1, as 3 is converted 
to a number before the 
non-add math function -
c) 3, as null is converted
to zero before the math
function
d) 3null, as null is converted to the string 
"null" before the concatenation of strings.
e) 4, as true is converted
to 1 before the add function
f) 0, as false and null are
converted to 0 before
the add function
g)NaN, as undefined cannot
be converted into a number
h)NaN, as the string '3'
is converted to a number 
but undefined cannot be 
converted

14. 
a) true, as the number 2
is greater than lthe number
1
b) false, as the string '12' comes before the string '2' alphabetically
c) true, as converting the number to the string
(or vice versa) will result in equal value
d) false, as strictly speaking the string 2
and the int 2 are not the same value
e) false, as true
is numerically converted to one
which is not equal to 2.
f) true, as Boolean(2) evaluates to true, which is 
the exact same as the boolean
true.

15. The == will typecast the first value to the type
of the second value before making a comparison,
allowing values of different types to return true.
=== will only return true if the two values are of the same type and same value.

17. For each element in the array [1, 2, 3], the 
function modifyArray will call doSomething, 
which doubles the value.  Therefore [2, 4, 6] will
be returned.

19. 
1
3
4
2

