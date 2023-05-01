### Part 1 Answers

1. Line 9 prints "values added: 20", with 20 being the output of the variable ```result```.
2. Line 13  prints out "final result: 20", with 20 being the output of the variable ```result```.
3. Line 9 now prints out "values added: 20", with 20 being the output of the variable ```result```. 
4. Since we used the ```let``` declaration, the variable was only defined in the the block scope of the if statement. In line 13, result is called outside the scope of the if statement which is why the code returns an error where result is not defined. 
5. The code returns an error because by using ```const``` declaration, we are unable to reassign the initial value that it was assigned to. The code never reaches line 9 as in line 7 we attempt to reassign the const variable ```result```.
6. The code returns an error because by using ```const``` declaration, we are unable to reassign the initial value that it was assigned to. The code never reaches line 13 as in line 7 we attempt to reassign the const variable ```result```.