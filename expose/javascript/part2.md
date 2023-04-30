# Part 2
1. It prints 3 at line 12, since variable i is declared with var, meaning that it has a function-scope. In addition, variable i would become 3 after the completion of the for loop since prices.length is 3
2. It prints 150 at line 13, since discountedPrice would be updated to price[2] * (1 - 0.5) = 300*0.5 = 150 in the last iteration of the for loop.
3. It prints 150 line 14, since, in the last iteration, finalPrice = Math.round(discountedPrice * 100) / 100 = 150*100/100 = 150
4. This function would return the list [50, 100, 150], since there would be one finalPrice pushed into the list for each iteration. For each element in the parameter list, it would be multiplied by 0.5 and be added to the list to be returned (note that line 8 does nothing since all elements in the parameter list are integers). Therefore, the returned would simply be the parameter list with every element multiplied by 0.5
5. It would throw an error at line 12, since i is declared with let, meaning that it only has block-scope inside the for loop
6. It would throw an error at line 13, since discountedPrice is declared with let, meaning that it only has block-scope inside the for loop
7. It would return 150 with the same reason as number 3. One thing to note is that it would not throw an error since line 14 is within the block-scope of finalPrice, which is the function of discountedPrice
8. This function would return the list [50, 100, 150] with the same reason as number 4. Note that switching from var to let for variable declaration would not affect anything in this case
9. It would throw an error at line 11, since i is declared with let, meaning that it only has block-scope inside the for loop
10. It would print 3, since the length of the input list is 3
11. It would return the list [50, 100, 150] with the same reason as number 4 and number 8. One thing to note is that making variable const would not affect the result of this function since no variable gets assigned to other value after its declaration
12. 
```
A. student.name
B. student['Grad Year']
C. student.greeting()
D. student['Favorite Teacher],name
E. student.courseLoad[0]
```

```
A. '32', since integer 2 gets converted to '2' gets concatenated after '3'
B. 1, since '3' gets converted to integer 3 and 3 - 2 = 1
C. 3, since null gets converted to 0 in integer, and 3 + 0 = 3
D. '3null', since null gets converted to string 'null' and gets concatenated behind '3'
E. 4, since true gets converted to 1 in integer, and 1 + 3 = 4
F. 0, since both false and null get converted to 0, and 0 + 0 = 0
G. '3undefined', since undefined gets converted to string 'undefined' and gets concatenated behidn '3'
H. NaN, since no available conversion exist for such operation
```
14.  
```
A. true, since '2' gets converted to 2 in integer, and 2 > 1 is true
B. false, since this is a string comparison, and '2' is in fact greater than '12' in terms of string
C. true, since '2' gets converted to integer 2 first, and 2 = 2 is true
D. false, since '===' is a string equality operator and it checks two operants wihtout type conversions
E. false, since true gets converted to 1 first, and 1 == 2 is false
F. true, because Boolean(2) evaluates to true first, and true === true is true
```
15. '==' is just a normal equality operator, while '===' is a strictly equality operator. The main difference is that '==' allows type conversion when two operands are different data types but '===' would immediately return false when data types are different 
16. check part2-question16.js
17. It should return the list [2,4,6]. Inside modifyArray, we iterate through each element inside the parameter array, multiply each of them by two according to the doSomething function, and add the new element into the returned list. At the end, the list that gets returned is simply the input list with every element multiplied by 2.
18. check part2-question18.js
19. 
```
1
4
3
2
```

