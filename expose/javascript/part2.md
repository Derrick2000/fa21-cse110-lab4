1. It will print 3. Because i is declared as a var type so it can be access outside of the block. Also it is looped 3 times since prices.length equals 3

2. 150. The value of the output variable "discountedPrice" is reassigned within the for loop. After the for loop it would remain what the last value of i is, which is 2: "price[2] * (1 - discount) = 300 * 0.5 = 150.

3. 150. Again, although the output variable "finalPrice" was initially declared as 0, it changes value within the for loop. Eventually, its value would be the last value of i, which is 2: and we already know the value of discountedPrice from question 2: 150. Our final output is: Math.round(150 * 100)/100 = 150

4. [50,100,150]. Its return value is the array whose values are calculated within the for loop.

5. Error. Because variables declared as let cannot be accessed outside of the block, which in this case is the for loop. 

6. Error, same thing above, the output variable is declared as let.

7. 150. Because the variable is not declared in the for loop, it can be accessed within the same block

8. [50,100,150]. discounted is declared and returned within the same block.

9. Error. i is declared as let and cannot be accessed outside of the for loop.

10. 3. The value of "length" is constant and is equal to the length of prices array.

11. [50,100,150]. Although the variable "discounted" was declared as const, pushing values are allowed


12. A) student.name
    B) student['Grad YR']
    C) student.greeting()
    D) student['Favorite TA'].name
    E) student.courseLoad[0]

13. A) '32'.            2 becomes a string added after '3'
    B) 1.               '3' becomes an integer 3 
    C) 3                null is considered 0
    D) '3null'          null is considered as a string added after '3'
    E) 4                rue is considered as integer 1
    F) 0                false is considered as integer 0
    G) '3undefined'     undefined is considered as a string added after '3'
    H) NaN              undefined cannot be considered as an numerical or integer value.

14. A) true     '2' is considered as an integer 2
    B) false    '2' -> 2, '12' -> 12
    C) true     '2' -> 2
    D) false    2 is not strictly equal to '2', they are different types
    E) false    true == 1
    F) true     Boolean(2) is the value true, and it is strictly equal to true

15. == does type conversion before comparing while === does not.

17. [2,4,6]. After the last line called modifyArray with parameters, in modifyArray function it creates a new output array that goes through the given array. Within the for loop, the value is modified in doSomething function (*2). Thus, the final array would have twice value each compared with the given array.

19. 1
    4
    3
    2