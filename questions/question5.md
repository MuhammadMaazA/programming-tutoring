# Question 5 (total 12 marks)


#### Exercise 1:
Write a C program that:

a) Declares and initializes one integer and one character, then declares and initializes two pointers, one for the integer and one for the character.

b) For each variable, print its value, address, and memory size (in bytes).

c) For each pointer, print its value, address, and the value it is pointing to.

d) Using only pointers, increment the integer by 5 and change the character to the next letter in the alphabet. Now print the updated values.

**(1+1+1+1 marks)**

#### Exercise 2:
Write a C program to perform search and delete **all occurrences** of an element in an array. The program should do the following:

a. Ask the user to enter the size of array. Followed by asking the user to input elements in array.

   Print the entered array. Then ask the user to enter the element to search within the array. **(2 marks)**

b. Search for the element in the array. Count and print how many times it appears in the array.
   
   Make sure to handle the 'not found' condition.
   
   **Hint:** Use sequential search (linear scan) to count occurrences. **(4 marks)**

c. Delete **ALL occurrences** of the element from the array and print the updated array after deletion.
   
   **Hint:** Keep a record of array size and shift elements. **(2 marks)**

**Sample output 1:**
```
Enter the size of array: 6
Enter the elements of the array: 5 3 5 8 5 2
The entered array is: 5 3 5 8 5 2
Enter the element to search: 5
5 is present 3 times in the array.
The array after deletion is: 3 8 2
```

**Sample output 2:**
```
Enter the size of array: 5
Enter the elements of the array: 4 7 9 1 3
The entered array is: 4 7 9 1 3
Enter the element to search: 6
6 is not present in the array.
```

