# Part 1a
1. 20
2. 20
3. 20
4. Error - This is because declaring it as **let** makes its scope only be in the if statement block
5. Error - This is because assigning result as a constant it cannot perform the reassignment operation.
6. Error - This is because assigning result as a constant it cannot perform the reassignment operation.

# Part 1b
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