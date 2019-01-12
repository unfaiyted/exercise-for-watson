## Day 2 - Watson Exercises

1. Create a function that doubles the value of its input: `doDouble(number)`
    - Expected to double the value of the number passed through the function argument

1. Create a function that is called `total(value, taxRate)` 
    - Function will take in the dollar value as a number, as well as the current tax rate
       - 0.55 would be 55% taxes
    - Function will return the Subtotal
    - Function will return the total amount of the purchase after Taxes.

1. Create a function called `age()` which takes in 3 arguments: `year, month day`
    - Based on the input data

1. Expand on the last function age, creating new function called `getUsersAge()`
    - Create a function that incorporates age but asks for the user to input the arguments.
    - If the user inputs something that is not a number, handle that accordingly. 

1. Create a function that is called `getMax(array)`.
    - The function will return the maximum value from the array that is passed.

    ```js
        getMax([11,22,33,44])   // Returns 44
        getMax([55,11,16, 51]) // Returns 55    
    ```
1. Create a function that calculates a students average grade. The function called `averageGrade(array)`
    - Input is an array of numbers, the average grade it calculated. 
    - Depending on the value of the grade, return the grade that is given
    - Use standard American grading structure `(A+, A, A- .... D-, F)`
    -  Example final ouput would be "You have earned a B-, with a 81% "
    
1.  Create a function called add. 
    - This function will add two different numbers together and return total as a numeric. 

1. Create a function called subtract
    - This function will subtract the first argument from the second
    - Input is expected to be a numeric value
    - Return a numeric value

1. Create a function called multiply
    - This function will multiple the values together to create a total
    - The final value should return a numeric value

1.  Create a program called calculator.
    - Calculator will accept user input. 
    - User input will need to be able to handle one operation. Anything else will error.
    - Example: 
        
        ```js
        Calc > 4+5
        Calc > 9
        Calc ? Continue? Yes
        Calc > 4 + XMXasdf
        Calc > "Error not valid"
        ```
    - After each calculation calculator will ask if you want to continue. If the user says No. End program
    - Use the functions you created earlier to provide the add/subtract/multiple capabilities.
    - Add a divide function to make the calculator complete. 
