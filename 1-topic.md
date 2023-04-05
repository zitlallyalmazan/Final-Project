# Queue

![A Queue Data Structure](/Users/zitallyalmazan/Desktop/queue-data-structure-diagram.jpg)

## What is a Queue in Data Structure?

A Queue is defined as a linear data structure that is open at both ends and the operations
are performed in First In First Out (FIFO) order.

## FIFO Principle of Queue:

* A Queue is like a line waiting to purchase tickets, where the first person in line is the 
first person served. (First come first serve).
* Position of the entry in a queue ready to be served, that is, the first entry that will be 
removed from the queue, is called the front of the queue(sometimes, head of the queue), similarly,
the position of the last entry in the queue, that is, the one most recently added, is called the rear 
(or the tall) of the queue.

## Characteristics of Queue:

* Queue can handle multiple data.
* Queue can access both ends.
* Queue are fast and flexible

## Queue Representation:

Like stacks, Queues can also be represented in an array

## Extra Definitions:
* Queue: the name of the array storing queue elements.
* Front: the index where the first element is stored in the array representing the queue.
* Rear: the index where the last element is stored in an array representing the queue.

## Example: Minimum Cost of Ropes

The task is to connect the ropes with minimum cost. Given N size array arr[] contains the lengths of the
ropes.

* There are given N ropes of different lengths, we need to connect these ropes into one rope.
* The cost to connect two ropes is equal to the sum of their lengths.

**Input:**
n = 4
arr[] = {4, 3, 2, 6}

**Output:** 
29

**Explanation:**
We can connect the ropes in following ways.
1) First connect ropes of lengths 2 and 3.
Which makes the array {4, 5, 6}. Cost of
this operation 2+3 = 5. 
2) Now connect ropes of lengths 4 and 5.
Which makes the array {9, 6}. Cost of
this operation 4+5 = 9.
3) Finally connect the two ropes and all
ropes have connected. Cost of this 
operation 9+6 =15
Total cost for connecting all ropes is 5
+ 9 + 15 = 29. This is the optimized cost
for connecting ropes. 
Other ways of connecting ropes would always 
have same or more cost. For example, if we 
connect 4 and 6 first (we get three rope of 3,
2 and 10), then connect 10 and 3 (we get
two rope of 13 and 2). Finally we
connect 13 and 2. Total cost in this way
is 10 + 13 + 15 = 38.

## Problem to Solve:

Write a Python program to find the three largest
integers from a given list of numbers using the queue
algorithm. 

## Solution:

import heapq as hq
nums_list = [25, 35, 22, 85, 14, 65, 75, 22, 58]
print("Original list:")
print(nums_list)
# Find three largest values
largest_nums = hq.nlargest(3, nums_list)
print("\nThree largest numbers are:", largest_nums)
