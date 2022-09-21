# -CSC310-Project5

Assignment 5
When to Submit
Due: 11:59pm, 11/30/2020
What to Submit
Please prepare a PDF file to include your answers to each question. Please also prepare
ONE ha5.py file to include all your codes (if applicable) – clearly comment the corresponding
questions.
How to Submit
Submit your PDF file and ha5.py file using the Canvas.
The goal of this collection of assignment is to help you review (i) Priority Queue.
1, In lecture 8, we introduced the ADT for priority queues. What does each remove_min() call
return within the following sequence of priority queue ADT methods:
add(1,a), add(3,b), add(2,c), add(5,e), remove_min( ), add(4,j), add(9,k), remove min(), remove min()?
Please provide the returned keys only in your answers.
2. Let H be a heap storing 15 entries using the array-based representation of a complete binary tree. What
is the sequence of indices of the array that are visited in a preorder traversal of H? What about an inorder
traversal of H? What about a postorder traversal of H? Let us assume array indices start from 1.
3. Is it correct that a preorder traversal of a heap will list its keys in nondecreasing order? Also, is it
correct that a postorder traversal of a heap will list its keys in nonincreasing order? Please draw an
example of a heap to prove your answers.
4. The lecture slides and textbook introduced a recursion-based method for the upheap method for the
class HeapPriorityQueue. Please provide an NONRECURSIVE Python implementation of this method.
Note that:
 You might find the Python codes for the classes HeapPriorityqueue and PriorityqueueBase in
the attached folder: ha5_code. Please use these python files to start your coding.
 Your method will be used to replace this class method and thus should achieve the exactly
same objective for the class.
 In your submission of ha5.py file, please include the complete source codes for the modified
class HeapPriorityQueue.
5. Please develop a Python function HeapSortInPlace(S) which implements the in-place heap-sort
algorithm. The input argument S is an unsorted list of integers, e.g., S=[10, 3, 4, 1, 9, 2, 5]. Your function
should return a sorted list: [1,2,3,4,5,9,10]. S is not of fixed length. You might start your coding with the
provided python scripts in the folder: ha5_code. In particular, the class heap_priority_queue provides a
heap implementation in Python (you don’t have to use the nonrecursive method developed in the previous
question). Please include your function HeapSortInPlace(S) in the ha5.py file and import relevant classes.
