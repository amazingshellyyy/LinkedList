# LinkedList

## What is Linked List?
A list that is linked. 
A singly linked list container a set of nodes where they are linked. Each nodes has two elements: the value of the data and a pointer (reference to the next node in line).
the first node is called the head and the last node is called the tail.
Linked list are null teminated. When a node is pointing to null that means it is the tail of the list.

![linkedlist](https://media.geeksforgeeks.org/wp-content/cdn-uploads/gq/2013/03/Linkedlist.png)
(photo credit to GeeksforGeeks)


two types of Linked List
 - singly Linked List
 - doubly Linked List

```
//what an array may look like

const backet = ['apples','grapes','pears']


//what a linked list may look like ( pointing to the next one)

//linked list : apples --> grapes --> pears

```
JavaScript doesn't come with Linked List build in (but some other language does - eg. Java)



## Example of Linked List

1. Playlist of Songs (doubly linked list)
2. Image viewer (doubly linked list)

## Questions can be asked 

1. Insertion
  - When doing insertion with a linked List, we first will iterate the list till we find the node before the given index, and we reassign the pointer to the new node and the pointer of the new node will point to the original node which located at the given index.
2. Deletion
 - When doing deletion with linked List, we first iterate the list till we find the node before the given index, and reassign the pointer to point to the next node of the given index. 


