# Ten Functions For Watson

1. Define a function named addOne that takes in a single input. If the input is a number or a numeric string, 
    return the value plus one
    
     ```js
     addOne(0)                    // 1
     addOne(2)                    // 3
     addOne(-5)                   // -4 
     addOne(5.789)                // 6.789
    ```
        
2. Define a function named concat that takes in two input arguments. If both arguments are strings, then return the 
concatenated result. If two numbers are provided, then return the string concatenation of each set of numerals.
    ```js
    concat("dont", "fail")                // "dontfail"
    concat("connect", 4)                // "connect4"
    concat("hello", "world")            // "helloworld"
    concat(4, 2)                        // "42"
    ```

3. Write a function that takes in an 2 arrays.
   First array has first names, and second array has last names. 
   Returns one full name, randomly pick the first and last name on each run.
      
     ```js
    firstNames = ['Billy', 'Karen', 'Cindy', 'Omar'];
    lastNames = ['Sanders', 'Smith', 'Barnes', 'Conner'];
    
    nameGenerator(firstNames, lastNames); 
    ```

4. Create a Function that is called HighLow. Call that function when the program runs. 
    * Function will generate a random number
    * User will guess that value of the random number
    * Random number is between 1 and 100.
    * When the user inputs a guess tell them if the value is `Higher` or `Lower`
    * When the user guesses the correct value, let them know they did it! End function running.

5. Create a function called rollDice.
    * Ask the user how many sides the dice have.
    * Roll 2 dice based on the number of sides.
    * Return the 2 values of the dice as well as the total value of both dice.
    * Ask the user if they want to continue rolling the dice, 
    * End when the user says they are done.

6. Create a function called analyseString().
    * Function will take an input of a string.
    * Function will return the following:
        * length of the string, 
        * the number of spaces,
        * the number of capital letters.
        * the number of words in the string.
        
7. Create a function that converts a numeric input to a dollar value
    * 39.99 becomes $39.99
    * 3.1 becomes $3.10
    * 3 becomes $3.00

8. Write a function that returns the total surface area and volume of a box as an array: [area, volume].

9. Create a function that calculates the winner in a Rock, Paper Scissors game. 

    ```js
    rps('scissors','paper') // Player 1 won!
    rps('scissors','rock') // Player 2 won!
    rps('paper','paper') // Draw!
    ```
        
10. Create a function called sUpErCoOl(). This function will take a string as input.
    It will capitilize every other letter in the string.
    * For example, `sUpErCoOl("abcdef") = ['AbCdEf']`
