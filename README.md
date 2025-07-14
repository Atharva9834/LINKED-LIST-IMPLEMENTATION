# LINKED-LIST-IMPLEMENTATION

*COMPANY*: CODTECH IT SOLUTIONS

*NAME*: ATHARVA GULHANE

*INTERN ID*: CT04DF2093

*DOMAIN*: C Programming

*DURATION*: 4 WEEEKS

*MENTOR*: NEELA SANTOSH

##DESCRIPTION OF TASK

The task focused on designing and implementing a menu-driven C program to perform core operations on a singly linked list: inserting a node, deleting a node by value, and traversing the list to display its contents. This task deepened my understanding of dynamic memory allocation, pointers, and the fundamental concept of linked lists in data structures.

The first part of the program defined a structure named Node, which holds an integer data and a pointer next pointing to the next node in the list. The linked list itself is represented by a pointer to the first node, known as the head. Initially, the head is set to NULL to indicate an empty list.

The program offers three primary operations, each encapsulated in a dedicated function:

1️. Insert a node:
The insert function dynamically allocates memory for a new node using malloc. After assigning the given value to the node, it checks whether the list is empty. If empty, the new node becomes the first node (head). If not, it traverses to the end of the list and links the new node as the last element. This demonstrates dynamic growth of the list and how pointers help maintain the connections between nodes. A confirmation message is printed after each insertion.

2️. Delete a node by value:
The delete function searches for the first node whose data matches the given value. It keeps track of the current node (temp) and its previous node (prev). Once found, it adjusts the next pointer of the previous node to skip over the node to be deleted, effectively removing it from the list. If the node to delete is the first node, it updates head directly. Finally, it frees the memory allocated to the deleted node to prevent memory leaks. If the value does not exist in the list, it prints a message to notify the user.

3️. Traverse and display the list:
The traverse function prints the data of each node sequentially by following the next pointers from the head until reaching the end (NULL). If the list is empty, it displays an appropriate message. This provides a clear view of the current state of the list after each operation.

The main function implements a menu-driven interface that runs in an infinite loop. It displays options to the user: insert, delete, traverse, and exit. Based on the user's choice, it calls the corresponding function. Using scanf, the program takes user input for the choice and the value to insert or delete.

For implementation and testing, I used:

Visual Studio Code (VS Code): as the code editor, which provided syntax highlighting, integrated terminal, and debugging support.

GCC compiler: installed via MinGW on Windows, to compile the C source file into an executable.

Windows PowerShell: as the terminal to compile and run the program.

#OUTPUT

<img width="853" height="843" alt="Image" src="https://github.com/user-attachments/assets/25a0044c-919c-423c-94ed-4916ca218b77" />

