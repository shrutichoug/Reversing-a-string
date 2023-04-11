# Reversing-a-string
Reversing a string

Strings Strings are used for storing text/characters. For example, "Hello World" is a string of characters. Unlike many other programming languages, C does not have a String type to easily create string variables. Instead, you must use the char type and create an array of characters to make a string in C:

char test[] = "Hello World!";

Access Strings

Since strings are actually arrays in C, you can access a string by referring to its index number inside square brackets [].

printf("%c", test[0]);

Algorithm:

Ask user to input a string to be reversed. Store it in an array. Calculate the length of the string by using the strlen function. Apply a for loop from (counter variable= length-1) initially and decrementing the value till (counter variable>=0) , printing the array in reverse.
![image](https://user-images.githubusercontent.com/125783965/231102757-217a9fd4-cdb7-4075-9e71-0bf64455cba3.png)
