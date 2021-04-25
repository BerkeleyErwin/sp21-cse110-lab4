## Part 1a
1. 20
2. 20
3. 20
4. Error - This is because declaring it as **let** makes its scope only be in the if statement block
5. Error - This is because assigning result as a constant it cannot perform the reassignment operation.
6. Error - This is because assigning result as a constant it cannot perform the reassignment operation.

## Part 1b
1. It will print out **3** which is because we have 3 elements [100, 200, 300] which i will iterate through 0, 1, 2 and then terminate as the value **3**.
2. **150**, prints out the last discounted price calculated.
3. **150**, returns the final discounted price of the item calculated last after rounding.
4. The function will return the **discounted** array which contains the final discounted prices of all the objects after rounding. It will not print anything though.
5. Error because **i** is in the scope of the for loop and once it terminates **i** disappears. 
6. Error because **discountedPrice** is in the scope of the for loop and once it terminates **discountedPrice** disappears. 
7. **150** because it is within the scope of the program so it prints normally. Declared outside the for loop.
8. The function will return the **discounted** array which contains the final discounted prices of all the objects after rounding. It will not print anything though.
9. Error because **i** is in the scope of the for loop and once it terminates **i** disappears. 
10. **3** because that is the length of prices array and since it isn't assigned anything else it works.
11. The function will return the **discounted** array which contains the final discounted prices of all the objects. It will not print anything though. This works despite the fact the array is constant because javascript allows you to add elements to a const array and additionally the discountedPrice can change too because it is redeclared at each iteration of the loop.
12. A. student.name
    B. student['Grad Year']
    C. student.greeting()
    D. student['Favorite Teacher'].name
    E. student.courseLoad[0]
13. A.  > '3' + 2
        '32' (Integers map to their exact string representations)
    B.  > '3' - 2
        1 (conversion from string to numbers)
    C.  > 3 + null
        3 (null maps to 0)
    D.  > '3' + null
        '3null' (null as a string is null literal)
    E.  > true + 3
        4 (True maps to the value 1)
    F.  > false + null
        0 (false maps to 0 and null maps to 0)
    G.  > '3' + undefined
        '3undefined' (as a string undefined is undefined literal)
    H.  > '3' - undefined
        NaN (Conversion of undefined to a number is NaN)
14. A. > '2' > 1
        true (string 2 becomes a number 2)
    B. > '2' < '12'
        false (Alphabetically 2 is greater than 12)
    C. > 2 == '2'
        true (== allows for type conversion comparison so they are equal)
    D. > 2 === '2'
        false (=== strictly states that no type conversion is allowed an evaluated as is)
    E. > true == 2
        false (true converted to a number is 1)
    F. > true === Boolean(2)
        true (=== does not implicitly type convert but by saying explicitly Boolean(2) we type cast it to a boolean)
15. == allows implicit type conversion while === does not
16. See javascript file
17. The callback function allows to pass a function as a parameter which then calls the multiplication of times 2 to the element in the array which is then returned and is the result of the array. It contains the previous array with all the elements multiplied by 2.
18. See javascript file
19. 1 4 3 2

