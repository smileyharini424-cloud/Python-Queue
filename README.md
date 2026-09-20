# Python Queue

## Explanation

A Queue is a linear data structure that follows the **FIFO (First In, First Out)** principle.

The element inserted first is removed first.

Example:

```text
Enqueue: 10 → 20 → 30
Dequeue: 10
```

This program implements a queue using a Python list.

## Problem Statement

Write a Python program to implement a Queue using a list.

The program should support:

* Enqueue
* Dequeue
* Front
* Display

## Features

* Implements Queue using a list
* Follows FIFO principle
* Supports enqueue operation
* Supports dequeue operation
* Displays the front element
* Handles an empty queue

## How It Works

1. An empty list is created to represent the queue.
2. `enqueue()` adds an element to the rear of the queue.
3. `dequeue()` removes the first element.
4. `front()` displays the first element without removing it.
5. `display()` shows all queue elements.
6. A menu allows the user to select an operation.

## Technologies Used

* Python 3

## Data Structure Used

* Queue
* List

## Methods Used

* `append()`
* `pop()`
* `input()`
* `len()`

## Program Flow

1. Create an empty queue.
2. Display the menu.
3. Read the user's choice.
4. Perform the selected queue operation.
5. Continue until the user chooses Exit.

## Sample Input

```text
1. Enqueue
2. Dequeue
3. Front
4. Display
5. Exit

Enter your choice: 1
Enter element: 10

Enter your choice: 1
Enter element: 20

Enter your choice: 4
```

## Sample Output

```text
Queue: [10, 20]
```

For a dequeue operation:

```text
Enter your choice: 2
Dequeued element: 10
```

## Time Complexity

* Enqueue: O(1)
* Dequeue: O(n)
* Front: O(1)
* Display: O(n)

## Space Complexity

* O(n)

## Key Learning

* Understanding Queue
* Understanding FIFO
* Implementing queue operations
* Using Python lists as a queue
* Handling an empty queue
* Understanding time complexity

## File Location

```text
Python-Queue/queue.py
```

## Repository Structure

```text
Python-Queue/
│
├── queue.py
└── README.md
```

## Author

V.Harini
