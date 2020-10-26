The **list** module helps to implement Linked Lists.
As of now, *list* module only helps to implenent Singly-Linked_list and it also provides a class for nodes in the Linked List. 

The **list** module defines the following class (more classes to be added later):

*class* Singly_linked_list
> Constructor for a Singly Linked List. It will create a new Linked List instance on which we can perform
different class methods as mentioned below:

```python
from list import Singly_linked_list
list = Singly_linked_list()
```

### list Objects:
**list** object (Singly_linked_list) provides the following public methods described below:

Singly_linked_list.**push(val)**:
> Inserts a new node at the end of the Linked List. You need to provide the value/data (which is given as 'val' in the Node class) of the node as an argument.

Singly_linked_list.**pop()**:
> Removes the last (tail) node from the Linked list and return its value.

Singly_linked_list.**shift()**:
> Removes the first (head) node from the Linked list and return its value.

Singly_linked_list.**unshift(val)**:
> Inserts a new node at the beginning of the Linked List. You need to provide the value (which is given as 'val' in the Node class) of the node as an argument.

Singly_linked_list.**get(index)**:
> Gets the value of the node at a particular position/index (passed as argument).

Singly_linked_list.**set(index, value)**:
> Replaces the value of a node at a particular position/index with the new value (passed as argument).

Singly_linked_list.**insert(position, value)**:
> Inserts a new node at a particular position in the Linked List. Provide position and the value/data as argument.

Singly_linked_list.**remove(position)**:
> Removes a node from a given position (provided as argument).

Singly_linked_list.**reverse()**:
> Reverses the Linked List.

Singly_linked_list.**begin()**:
> Returns the value of the 'head' node.

Singly_linked_list.**end()**:
> Returns the value of the 'tail' node.

Singly_linked_list.**print_list()**:
> Prints the whole Linked List.
