### Part 1 Answers

1. At line 12, the code will print the value of ```i``` which is the iteration counter for the for loop. In this case, since there are three values stored in the price array andd the loop guard is ```i < price.length>```, the code returned 3. 
2. At line 13, the code will print out the value of the variable ```discountedPrice```. In this case the code printed out 150 because on the last iteration of the for loop, we assigned 300 * (1-0.5)  to ```discountedPrice```.
3. At line 14, the code will print out the last assigned value of the variable ```finalPrice``` in the last iteration of the for loop. In this case, the code printed 150 because in the last iteration we took the ```discountedPrice``` and rounded it to the nearest hundredth decimal. 
4. This function will return an array declared as ```discounted``` which contains the values of the ```prices``` array after the discount takes place. In this case, the ```discounted``` array would be [50,100,150].
5. Since we attempt to print the index variable of the for loop, ```i```, outside of the scope of the for loop, the code at line 12 causes an error due to the ```let``` declaration. 
6. The variable ```discountedPrice``` is declared within the for loop. Since we used ```let``` declaration, this means we are unable to access ```discountedPrice``` outside of the scope of the for loop. Therefore the code causes an error. 
7. The variable ```finalPrice``` is declared inside the function and outside of the for loop. In this case the block scope is the entire function. The code in line 14 prints out 150 which is the value of the ```finalPrice``` in the last iteration of the for loop. 
8. This code will return the array ```discounted``` which is defined in the function block scope. Since ```return discounted``` is called in the same block scope where it was defined, the code returns the array of discounted values. 
9. At line 11, the code will cause an error because the index variable ```i``` is declared in the loop guard of the for loop. This means that ```i``` is in the block scope of the forloop and cannot be called in ```console.log(i)```.
10. ```length``` is declared as a const variable with the value ```prices.length``` initially stored inside. Line 12 prints the number 3 which is initially assigned to the variable ```length```.
11. We are able to push new values into the array but ```const``` declaration will not allow us to reassign ```discounted``` to a new array. This function will return the array ```discounted``` with the values of the discounted prices. 
12. A. student.name  
    B. student['Grad Year'] <br>
    C. student.greeting() <br>
    D. student['Favorite Teacher'].name <br>
    E. student.courseLoad[0]
13. A. '3' + 2 = '32' since integers map to string representation and 2 is concatenated to the string '3'.
    B. '3' - 2 = 1 since '3' is changed to an int and subtracted by 2. <br>
    C. 3 + null = 3 since null is represented by the 0 as an int so 3+0 = 3. <br>
    D. '3' + null = '3null' as null is changed to its string representation 'null' and concatenated to the string '3' <br>
    E. true + 3 = 4 since int representation of true is 1 so 1+3 = 4. <br>
    F. false + null = 0 since the int representation of both true and null is 0. <br>
    G. '3' + undefined = '3undefined' because  the string representation of undefined is  'undefined' and it is concatenated to '3'. <br>
    H. '3' - undefined = NaN because undefined cannot be represented as an integer so it would be unable to subtract from 3. 
14. A. '2' > 1 would return true as the int representation of '2' is greater than 1.    
    B. '2' < '12' would return true as the char size of the string '2' is smaller than the char size of the string '12' <br>
    C. 2 == '2' returns true because == performs type conversion before comparing so it would convert '2' to 2. <br>
    D. 2 === '2' returns false because === does not perform type conversion and 2 and '2' are different types. <br>
    E. true == 2 would return false as true would be converted to 1 and 1 != 2. <br> 
    F. true === Boolean(2) is true since any nonzero value will be converted to true when using Boolean(2). Therefore no conversion will be needed. <br>
15. The difference between the ```==``` and the ```===``` operators is that ```===``` is a strict inequality operator that does not perform any type conversions. ```==``` on the other hand does perform type conversions before comparison. 
16. part2-question16.js
17. In the for loop of the function ```modifyArray```, it pushes the value of doSomething, which takes in the input of the current value in the array newArr at index ```i``` and returns a value. The value of doSomething() is defined in its function where it takes a num and multiplies it by 2. This means that each of the values of array will go through the function doSomething and return the number multiplied by 2. That value will then be pushed into ```newArr```. Since our input array is [1,2,3], the function will return [2,4,6].
18. part2-question18.js
19. The output of the code is 1,4,3,2. 1 will first be output and then it will set a timeout for 2  at 1000 milliseconds and a timeout for 3 at 0 milliseconds. 4 will then be output and then the timeouts will commence. 3 will output since it has a timeout of 0 milliseconds and then after a timeout of 1000 milliseconds, 2 will be output last. 
