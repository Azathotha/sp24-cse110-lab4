1. It will print 3, as i will have a value of 3 after the loop finishes.
   
2. It will print 150. In the last iteration of the loop, the discountedPrice = 300 * (1 - 0.5) = 150.
   
3. It will print 150. In the last iteration of the loop, the finalPrice = (150 * 100) / 100 = 150.
   
4. [50, 100, 150], the array of discounted prices. The function uses an array of prices and a discount value as input, use a for loop to calculate discounted prices for each price, then append them to a discounted list and return it.
   
5. error. Because i is declared inside the scope, so it's not accessible outside of it.
   
6. error. Because discountedPrice is declared inside the scope, so it's not accessible outside of it.
   
7. It will print 150. In the last iteration of the loop, the finalPrice = (150 * 100) / 100 = 150.
   
8. [50, 100, 150], the array of discounted prices. The function uses an array of prices and a discount value as input, use a for loop to calculate discounted prices for each price, then append them to a discounted list and return it.
   
9.  error. Because i is declared inside the scope, so it's not accessible outside of it.
    
10. It will print 3, as the length of the array is 3.
    
11. [50, 100, 150], the array of discounted prices. The function uses an array of prices and a discount value as input, use a for loop to calculate discounted prices for each price, then append them to a discounted list and return it.
    
12. A. student.name
    B. student['Grad Year']
    C. student.greeting()
    D. student['Favorite Teacher'].name
    E. student.courseLoad[0]

13. Arithmetic
    A. '3' + 2 : '32'
    In JavaScript, when you use the + operator with a string and a number, it 
    performs string concatenation. So, '3' + 2 results in the string '32'.
    B. '3' - 2 : 1
    Using - operator with a number and a string that can be converted to a number, 
    JavaScript converts the string to a number.
    C. 3 + null : 3
    when you use the + operator with a number and null, null is treated as 0. So, 3 + 
    null equals 3.
    D. '3' + null : '3null'
    '3' is a string, the + operator performs string concatenation. null is converted 
    to the string 'null', so '3' + null equals '3null'.
    E. true + 3 : 4
    In JavaScript, true is internally represented as 1, and when you add 1 to 3, you 
    get 4.
    F. false + null : 0
    false is internally represented as 0, and when you add 0 to null, you get 0.
    G. '3' + undefined : '3undefined'
    '3' is a string, so the + operator performs string concatenation. undefined is 
    converted to the string 'undefined', resulting in '3undefined'.
    H. '3' - undefined : NaN
    Using - operator with undefined and a string that can be converted to a number, 
    JavaScript converts the string to a number, which converts '3' to 3, and converts 
    undefined to NaN. when you perform a mathematical operation with NaN, the result 
    will always be NaN. So, 3 - NaN will result in NaN.

14. Comparison
    A. '2' > 1 : true
    When comparing strings and numbers using the > operator, JavaScript converts the 
    string to a number. So, '2' > 1 becomes 2 > 1, which is true.
    B. '2' < '12' : false
    When comparing strings, JavaScript compares them character by character.'2' 
    is greater than '1', so '2' < '12' is false.
    C. 2 == '2' : true
    The == operator converts '2' to a number 2, so 2 == '2' is true.
    D. 2 === '2' : false
    The === does not perform type conversion, since '2' and 2 have different types, 
    '2' === 2 is false.
    E. true == 2 : false
    The == performs type convention, converts true to 1. So, 
    true == 2 becomes 1 == 2, which is false.
    F. true === Boolean(2) : true
    The Boolean(2) returns true, true === true is true.

15. Explain the difference between the == and === operators.
    The equality operator == converts operands of different types to numbers before 
    comparing them. While the strict equality operator === checks the equality without 
    type conversion, if a and b are of different types, then a === b immediately 
    returns false.

16. part2-question16.js

17. [2, 4, 6]. When called modifyArray with the array [1, 2, 3] and the doSomething callback function, it doubles each element, resulting in [2, 4, 6].

18. part2-question18.js

19. 1
    4
    3
    2





    