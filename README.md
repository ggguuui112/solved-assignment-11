Download Link: https://assignmentchef.com/product/solved-assignment-11
<br>
<p class="ui header product-top-header" title="Assignment #11 Solution">Assignment #11 will be the construction of a program that takes an input string, and check if parentheses and braces in each string are matching or not.

The method checking() in the Matching class needs to check if parentheses and braces in the parameter string is matching or not using an object of the Stack class in java.util package.

Instruction:

Assignment11 classThis class displays a menu for the parentheses or braces checking. If a user enters “P”, then it asks to enter a string. This class is given by the instructor.

Matching classYou need to complete the following method.

public static int checking(String inputString)

You need to write the checking method that takes an input string, and read every character from its left to right, then returns 0, 1, 2, 3, or 4 based on the following description.

It should create an empty Stack object at the beginning, and if a character is a left parenthesis ‘(‘ or a left brace ‘{‘, then push it (or its corresponding string such as “(” or “{“) onto the stack.

If a character is a right parenthesis ‘)’ and the top of the stack is ‘(‘, then pop it and continue to process the next character of the input string. But if the top of the stack is not ‘(‘ or the stack is empty, then that means that there was no matching left parenthesis, thus the method should return 1.

If a character is a right brace ‘}’ and the top of the stack is ‘{‘, then pop it and continue to process the next character of the input string. But if the top of the stack is not ‘{‘ or the stack is empty, then that means that there was no matching left parenthesis, thus the method should return 3.

After reading all characters of the input string, if the stack is empty, then it means that everything is matching, the method should return 0.

After reading all characters of the input string, if the stack is not empty, and the top of the stack is a left parenthesis ‘(‘, then there was no matching right parenthesis, thus the method should return 2.

After reading all characters of the input string, if the stack is not empty, and the top of the stack is a left brace ‘{‘, then there was no matching right brace, thus the method should return 4.

The error messages are based on the first parenthesis or brace from left of the input string that does not have any matching.

Requirements:

You need to implement this method using an object of the Stack class) in java.util package.

<span class="kksr-muted">Rate this product</span>