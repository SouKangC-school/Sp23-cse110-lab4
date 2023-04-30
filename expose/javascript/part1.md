# Part 1
var declaration:
1. 20
2. 20

let declaration:
1. 20
2. error, since result is declared by let, which means it only has block scope inside the if statement. However, line 13 is outside the if statement.

const declaration:
1. error, since line 7 is trying to change the value of const variable result, which is prohibited
2. error, same reason as above. Notice that the function would terminate as early as line 7, so it would not even reach line 13 when the error is returned. 

 