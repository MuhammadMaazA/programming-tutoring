# Question 6 (total 12 marks)

#### Exercise 1:
Write a C program that:

a) Declares and initializes three integers (x, y, z) and then declares and initializes three pointers, one for each integer.

b) For each integer, print its value and address.

c) For each pointer, print its value and the value it is pointing to.

d) Using only pointers, calculate x = x + y - z and store the result in x. Then swap the values of y and z using pointers. Now print the final values of x, y, and z.

**(1+1+1+1 marks)**

#### Exercise 2:
Write a C program to insert an element at a specific position in an array. The program should do the following:

a. Ask the user to enter the size of array. Followed by asking the user to input elements in array.

   Print the entered array. Then ask the user to enter a position (index) and the element to insert at that position. **(2 marks)**

b. Check if the position is valid (0 to size). If invalid, print an error message.
   
   **Hint:** Valid positions range from 0 to the current size of the array. **(4 marks)**

c. Insert the new element at the specified position, shifting all elements after that position one place to the right. Print the updated array after insertion.
   
   **Hint:** Start from the end and shift elements backwards. **(2 marks)**

**Sample output 1:**
```
Enter the size of array: 4
Enter the elements of the array: 10 20 30 40
The entered array is: 10 20 30 40
Enter the position to insert: 2
Enter the element to insert: 25
The array after insertion is: 10 20 25 30 40
```

**Sample output 2:**
```
Enter the size of array: 3
Enter the elements of the array: 5 10 15
The entered array is: 5 10 15
Enter the position to insert: 5
Invalid position! Position must be between 0 and 3.
```
