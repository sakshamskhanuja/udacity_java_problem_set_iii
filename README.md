## Problem Set

### Question 1

Write a Java function called ```absoluteValue()```. The access modifier should be ```public```, it should have a return type of ```double```, and it should take one double parameter as input. If the double parameter is less than 0, it should return that number negated. Otherwise, it should return the parameter unchanged.

### Question 2

Write a Java function named ```calculateTip()```. The access modifier should be ```public```, it should have a return type of ```double```, and it should take as input a double parameter representing the cost of a meal at a restaurant. And finally, it should return a double equal to 15% of the cost parameter.

### Question 3

Write a Java function called ```nametagText()```. The access modifier should be ```public```, the return type should be ```String```, and it should take a String parameter called ```name```. In the body of the function, return the String "Hello, my name is " with the name parameter added to the end. (Hint: use String concatenation.)

### Question 4

Define two functions. The first should be called ```fahrenheitToCelsius()```. It should be a ```public``` function with return type double that takes a double argument that represents a temperature in Fahrenheit degrees. It should return the equivalent temperature in Celsius degrees. (To convert from Fahrenheit to Celsius, use the formula C = (F - 32) * 5/9.)

Next, define a function called ```printTemperature()```. It should be ```public```, it should have a return type of ```void```, and it should take a double parameter that represents a temperature in Fahrenheit degrees. This function should print "F: " followed by the Fahrenheit parameter, then "C: " followed by the equivalent value in Celsius degrees. Use the first function you defined to calculate the appropriate Celsius value inside the second function.

Bonus challenge: write javadoc comments for both functions.

### Question 5

Define a function called ```monopolyRoll()```. This function provides a random result based on the dice-rolling rules for the board game Monopoly. In Monopoly, players roll two six-sided dice to determine their move. If they roll the same value on both dice, this is called "rolling doubles," and it means they go again. In our simplified version, the dice-roll function should behave like this:

1. Generate two random integers in the 1 to 6 range.
2. If the numbers are not the same, return the sum.
3. If the numbers are the same, generate two more random integers in the 1 to 6 range, and return the sum of all 4 numbers.

 Hint: to make your code neater, you can define a second function that generates a random integer in the 1 to 6 range (or in the 1 to x range based on a parameter) so that you do not need to keep repeating that code.
