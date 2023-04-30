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
