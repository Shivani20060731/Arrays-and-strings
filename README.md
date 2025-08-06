# Arrays-and-strings

Aim:

To study and implement Arrays and Strings in C++.

Tools Used:

VS Code or Programiz online C++ compiler

Theory

Arrays in C++

An array is used to store multiple values of the same type.

All elements are stored in continuous memory.

Each element is accessed using an index starting from 0.

The size of the array is fixed when created.


Syntax:

data_type array_name[size];

Example:

int numbers[5] = {10, 20, 30, 40, 50};


---

Strings in C++

A string is a group of characters used to store text.

Strings can be created using:

Character arrays

or the string data type from the string library.


Strings are more flexible than arrays and support many operations like:

adding (concatenation)

comparing

finding length, etc.



Syntax:

string name = "Hello";
// or
string name;

Example:

string greeting = "Welcome";

 Experiments and Algorithms

7.1 Printing Array Elements

Algorithm:

1. Create an array with values.


2. Use a loop to go through each element.


3. Print each element one by one.

 7.2 Finding a Number in an Array

Algorithm:

1. Create an array and set a target number to search.


2. Loop through the array elements.


3. Compare each element with the target.


4. If found, print its position or index.


5. If not found, print "Not found".


7.3 Sum and Average of Array Elements

Algorithm:

1. Create an array with numbers.


2. Set a variable sum = 0.


3. Loop through the array and add each element to sum.


4. Calculate average = sum / total elements.


5. Print both sum and average.


7.4 Maximum and Minimum Element

Algorithm:

1. Create an array.


2. Set max and min to the first element.


3. Loop through the array:

If current element > max, update max.

If current element < min, update min.



4. Print both max and min.

 7.5 Declaring Strings

Algorithm:

1. Declare a string variable using string.


2. Assign some text to it.


3. Print the string.

7.6 Concatenation of Strings

Algorithm:

1. Declare two string variables with some text.


2. Join them using + operator or append() function.


3. Print the result.

 7.7 Reversing a String

Algorithm:

1. Declare and initialize a string.


2. Loop through it in reverse (from last to first).


3. Build a new string with reversed characters.


4. Print the reversed string.






