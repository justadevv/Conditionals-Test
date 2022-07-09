# Conditionals-Test

# Do all of your work inside of index.js. Check your work as you go with the console, the command in the console to run to check it, is node index.js

--Instructions-- 
1. Write a variable, named favoriteColor, that could potentially have it's value changed in the future. Set the value to currently be 'blue'.

2. Reassign favoriteColor to a different color of your choosing. 

3. Write another variable, one that will never have it's value change, and call it myName, and set the value equal to your name. 

4. Log the values of both favoriteColor and myName to the console.

5. Log to the console "My favorite color is favoriteColor" using string interpolation, to replace favoriteColor with the value that's assigned to it.

6. Write down if these statements evaluate to true or false. Pay attention to strict or loose equals.
    a. 12 >= 7
    b. 13 === 13
    c. "cat" !== "dog"
    d. 17 == "17"


7. Write down 3 of the 6 "falsey" values.

8. Make a variable named isHungry and set it equal to true. Then write an if..else statment that returns "Time to eat!" if hungry is true, or that returns "Keep coding!" if hungry is false.
(Remember, we only need to === in our if statement if we're checking to see if a string matches, like we did with if food === 'tacos', for example.)

9. Rewrite the if..else from number 8 as a ternary operator. 

10. Make a function named currentSeason and give it a perameter of season. Inside of this function, make an if..else statement that does the following:
        if currentSeason is summer, return a string saying "It's hot and humid"
        if currentSeason is fall, return a string saying "The leaves are changing colors!"
        if currentSeason is winter, return a string saying "I hope it snows!"
        if currentSeason is spring, return a string saying "It's raining a lot!"
        else return a string saying "That's not a season!"
(The hint from number 8 can really be handy on this problem!)

**Bonus**
1. Make number 10 into a switch statement, below you will find the syntax for a switch, to help you get started. Don't forget the default statement at the end!

    switch(parameterHere) {
        case: 'season':
            return 'string'
            break;
    }

2. Do you remember how to push it back to github? I'll give you a hint: Replace the blanks with the words. Each blank represents 1 letter. Like cat would be ---
    git --- .
    git commit -- "finished"
    git ----