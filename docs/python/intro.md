# Python: Intro
### First day challenges
Try to do as many of these on your own as you can! Don't be afraid to search in your toolkit for ideas.
1. Create a variable “x” with a value of 10.
2. Get a sprite and a background.
3. Make the sprite go to 3 different positions. For an extra challenge, make the positions random.
4. Print out “Hello world!” to the console.
5. Print out your variable “x” to the console.
6. Print out the x and y coordinate of the sprite in the console.
7. Print out the numbers 1 through 10 to the console. Hint: Use a loop.
8. Make the sprite follow the mouse pointer. Hint: the sprite will need to go to the cursor when the mouse moves.
9. Add in a second sprite that
    * Goes to a new random position every 2 seconds
    * Every time it moves, it should print out its new location in the console
11. Check if the sprites hit one another. If they hit each other, one of them should say "ouch".
12. Add in a variable that keeps track of how many times the sprites have hit each other.
13. If the sprites have hit each other 10 times, they should stop moving and text saying "Game over" should appear on the screen.
14. Ask the user for a number and print it out to the console with the text "Number: ".
15. Add a display so that there is always text on the screen showing the number of times that the sprites have hit one another.
16. Ask the user for a number and check if it is even or odd. If it is even, print out "even number". Otherwise, print out "odd
number".

### Second day challenges
#### Challenge 1
Write a Python program that will ask the user to enter a grade. The program should tell them their grade and comment on how well they did. The grade has to enter a whole number between 0 and 100, otherwise the input will count as invalid. 

**Hint:** You'll want to use a command such as:

```grade = int(input("Please enter your grade (0-100): "))```

Use the ranges and descriptions in the table below:

| Grade | Scale  | Description        |
| ----- | ------ | ------------------ |

| A     | 90-100 | Excellent          |
| B     | 80-89  | Very Good          |
| C     | 70-79  | Improvement Needed |
| D     | 60-69  | Close Fail         |
| F     | 0-59   | Fail               |

#### Challenge 2
Write a Python program that uses a For loop to go through every number from 0 to any number from 10-20. The program should check and count how many odd numbers and even numbers there are, then print the answers.

**Hint:** to check if a number is even, you can use the modulo formula.

```if (number % 2 == 0)```

#### Challenge 3
Write the same program as above, but this time use a While loop!

