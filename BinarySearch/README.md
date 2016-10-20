# Binary Search

Binary search allows us to search for a value within a sorted array with O(logn) complexity.  This is a vast improvement from using a basic for loop.  How it works is by looking at the middle value of an array.  If the value you are looking for is above the middle value, repeat for the top half of the array.  If it is below, than repeat for the bottom half of the array.

There are two valid ways of writing this method - recursive or iterative.  I'm posting recursive first.  I may go back and show an iterative version as well.

In order to keep the input consistent across languages, I'm reading it in from a text file.  This is hardcoded into the program, and may be changed.

# Running Instructions
###C++:

Compile: `g++ BinarySearch.cpp -o BinarySearch`

Run: `./BinarySearch <target>`

###Java:

Compile: `javac BinarySearch.java`

Run: `java BinarySearch <target>`
