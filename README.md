# Linear data structures

## Nodes

Nodes are the fundamental building blocks of many computer science data structures. They form the basis for linked lists, stacks, queues, trees, and more.

An individual node contains data and links to other nodes. Each data structure adds additional constraints or behavior to these features to create the desired structure.

## Linked Lists

Linked lists are one of the basic data structures used in computer science. They have many direct applications and serve as the foundation for more complex data structures.

The list is comprised of a series of nodes. The head node is the node at the beginning of the list. Each node contains data and a link (or pointer) to the next node in the list. The list is terminated when a node’s link is null. This is called the tail node.

## Stacks

Stacks:
-   Contain data nodes
-   Support three main operations
    -   Push adds data to the top of the stack
    -   Pop removes and provides data from the top of the stack
    -   Peek reveals data on the top of the stack
-   Implementations include a linked list or array
-   Can have a limited size
    -   Pushing data onto a full stack results in a stack overflow
-   Stacks process data Last In, First Out (LIFO)

 **LIFO** is an abbreviation for **last in, first out**. It is a method for handling data structures where the **first element** is processed last and the **last element** is processed first.

##  Queues

Queues:
-   Contain data nodes
-   Support three main operations:
    -   Enqueue adds data to the back of the queue
    -   Dequeue removes and provides data from the front of the queue
    -   Peek provides data on the front of the queue
-   Can be implemented using a linked list or array
-   Bounded queues have a limited size.
-   Enqueueing onto a full queue causes a queue overflow
-   Queues process data First In, First Out (FIFO)

**FIFO** is an abbreviation for **first in, first out**. It is a method for handling data structures where the **first element** is processed first and the **newest element** is processed last.
