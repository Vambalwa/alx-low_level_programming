Singly Linked Lists
Quiz
What’s a node? (select all possible answers)

It’s a structure with a pointer to the next node and value information
It’s a space allocated in memory

Question #1
What is the “head” of a linked list?
It’s the first node

Question #2
What’s the “tail” of a linked list?
It’s the node with the pointer to the next equals to NULL

Question #3
In a singly linked list, what are possible directions to traverse it? (select all possible answers)
Forward

Question #4
Arrays Vs Linked Lists: select all true statements
We can add elements indefinitely to a linked list
Linked list can contain as value a structure
Array can contain as value a structure
We can easily remove an element from a Linked list
Memory is aligned for an Array - each elements are back to back in the memory
0. Print list
mandatory
Write a function that prints all the elements of a list_t list.

Prototype: size_t print_list(const list_t *h);
Return: the number of nodes
Format: see example
If str is NULL, print [0] (nil)
You are allowed to use printf
1. List Length
mandatory
Write a function that returns the number of elements in a linked list_t list.

Prototype: size_t list_len(const list_t *h);

2. Add node
mandatory
Write a function that adds a new node at the beginning of a list_t list.

Prototype: list_t *add_node(list_t **head, const char *str);
Return: the address of the new element, or NULL if it failed
str needs to be duplicated
You are allowed to use strdup

3. Add node at the end
mandatory
Write a function that adds a new node at the end of a list_t list.

Prototype: list_t *add_node_end(list_t **head, const char *str);
Return: the address of the new element, or NULL if it failed
str needs to be duplicated
You are allowed to use strdup

4. Free list
mandatory
Write a function that frees a list_t list.

Prototype: void free_list(list_t *head);

5. The Hare and the Tortoise
Write a function that prints You're beat! and yet, you must allow,\nI bore my house upon my back!\n before the main function is executed.

You are allowed to use the printf function

6. Real programmers can write assembly code in any language
#advanced
Write a 64-bit program in assembly that prints Hello, Holberton, followed by a new line.

You are only allowed to use the printf function
You are not allowed to use interrupts
Your program will be compiled using nasm and gcc:
