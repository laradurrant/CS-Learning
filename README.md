# CS-Learning
A small hub of learning materials for basic computer science concepts

Topics to cover:
## Algorithms
  * “Big O Notation” or AKA “Runtime complexity”
    * [Big theta vs Big O](https://www.khanacademy.org/computing/computer-science/algorithms/asymptotic-notation/a/big-o-notation)
    * Big O is used when we want to bound only from above
      * Example) You say you have less than a million dollars in your pocket. Reality: You have $10. It's true, but not  very precise.
    * Big omega notation is when we want to bound from below
      * Example) I have more than $10 in my pocket.
    * A way to classify algorithms & how long they take to run
    * [Guide from Interview Cake](https://www.interviewcake.com/article/java/big-o-notation-time-and-space-complexity)
    * [Guide from MIT](http://web.mit.edu/16.070/www/lecture/big_o.pdf)
  * Linked Lists
    * Contains nodes, each node has a value and a pointer to the next value in the list
    * Singly linked lists are unidirectional, where doubly linked lists contain two pointers (one to the previous and next nodes)
    * Adding to the front or the end of the list is quite easy and efficient
    * However, adding to the middle of a linked list can be tricky unless you have the address of the node you want
    * The reason for this is because you have to cycle through every element in order to find the spot that you want
  * Linear Search
    * What would happen if you searched every item from start to finish
    * So in a number choosing game, you would start with 1, 2, 3, 4, 5, etc
    * Worst case scenario, you will go through the entire list -> Θ(n)
    * [Aymptotic notation](https://www.khanacademy.org/computing/computer-science/algorithms/asymptotic-notation/a/big-big-theta-notation)
  * Binary Trees
    * An efficient search algorithm that divides a sorted list in half 
      * Commonly used in a lot of guessing games
      * Can be used for maze pathfinding with a grid
      * This is the algorithm we used in the Number Wizard game from Udemy
      * With a list of numbers between 1 and 100, you would want to guess 50 first, then 25, etc
      * At worst, you will check log2(n) + 1 or log2(n) cases
  * Merge Sort
    * Merge sort is a divide and conquer type of algorithm
    * Can be run recursively--> idea is that you break the array up into smaller arrays
    * So an array of length 20 would become two arrays of length 10, etc
    * The process would then repeat until the length of each array becomes 1.
    * At this point, the values of the arrays are sorted and then combined
  * Quick Sort
  * Bubble Sort
 
 Possible Resources:
 * [Simple Algorithms](http://algorithms.openmymind.net/)
 * [Khan Academy - Algorithms](https://www.khanacademy.org/computing/computer-science/algorithms)
 * [Quora - 10 common algorithms for CS Students](https://www.quora.com/Which-are-the-10-algorithms-every-computer-science-student-must-implement-at-least-once-in-life)
 
## Memory Management & Pointers
Pointers are a way to keep track of the address of a variable within memory. 

* [Pointers in C++ - Tutorial](http://www.cplusplus.com/doc/tutorial/pointers/)
* [Memory Management Wikipedia](https://en.wikipedia.org/wiki/Memory_management)
* [C++ Programming / Memory Management](https://en.wikibooks.org/wiki/C%2B%2B_Programming/Memory_Management)
* [C++ Memory Management isn't the Boogie Man You Think It Is](http://www.gamefromscratch.com/post/2013/04/02/CPP-memory-management-isnt-the-boogie-man-you-may-think-it-is.aspx) 
