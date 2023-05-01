### Part 3 Explore
1. The bug was that the code was reading num1 and num2 as string literals and instead of adding, it was concatenating the two numbers
2. To fix it, I would replace ```num1+num2``` in the calculateSum function with ```parseInt(num1) + parseInt(num)```. This way the code knows the read the inputs as integers and to calculate the sum accordingly. 