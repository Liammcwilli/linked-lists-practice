# Linked List Implementation in JavaScript

This project contains a basic implementation of a linked list in JavaScript. The code consists of two main classes: `Node` and `LinkedList`.

## Node Class

The `Node` class represents individual nodes in the linked list. Each node contains:

- `data`: Holds the value of the node.
- `next`: Points to the next node in the list.

### Methods

- `setNextNode(node)`: Sets the reference to the next node.
- `getNextNode()`: Retrieves the reference to the next node.

## LinkedList Class

The `LinkedList` class manages the linked list, maintaining a reference to the head node.

### Methods

- `addToHead(data)`: Adds a new node containing the given data to the beginning of the list.
- `addToTail(data)`: Adds a new node containing the given data to the end of the list.
- `removeHead()`: Removes the head node from the list.
- `printList()`: Prints the entire list, from head to tail, for visualization.

## Usage

To use this implementation:

1. Import the `LinkedList` class from `./LinkedList`.
2. Create a new linked list instance.
3. Perform operations like adding nodes to the head or tail, removing the head, and printing the list.