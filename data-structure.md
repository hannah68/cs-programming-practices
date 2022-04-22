# Data structures
Data structures, at a high level, are techniques for storing and organizing data that make it easier to modify, navigate, and access. Data structures determine how data is collected, the functions we can use to access it, and the relationships between data.(Data structures are a way of storing and organizing the data primitives so that they can be efficiently accessed and used in algorithms.)

Data structures enable us to:
- Manage and utilize large datasets
- Search for particular data from a database
- Design algorithms that are tailored towards particular programs
- Handle multiple requests from users at once
- Simplify and speed up data processing

JavaScript has primitive and non-primitive data structures.

- Primitive data structures and data types are native to the programming language. These include boolean, null, number, string, undefined, bigInt, symbol.
- Non-primitive data structures are not defined by the programming language but rather by the programmer. These include linear data structures, static data structures, and dynamic data structures, like queue and linked lists.

1. Array
Arrays are sequences of primitive data types, similar to a list. In JavaScript, there are two common object-oriented implementations of array-like objects: stacks and queues, as well as the specially defined array object. Stacks and queues differ from the exact definition of arrays in other programming languages by how objects are added or removed.
Queues are FIFO (first in, first out) while stacks are LIFO (last in, first out). You can think of a queue as a line of people going into a store, where the first one in the line gets into the store, and a stack as a stack of files, with the last one placed on the stack being the first one out.

disadvantage:
- Fixed size
- Expensive to insert/delete or resequence values
- Inefficient to sort

2. Queues
Queues are conceptually similar to stacks; both are sequential structures, but queues process elements in the order they were entered rather than the most recent element.
As a result, queues can be thought of as a FIFO (First In, First Out) version of stacks. These are helpful as a buffer for requests, storing each request in the order it was received until it can be processed.
A queue has two main operations:
enqueue, which adds an element to the end (tail) of the collection
dequeue, which removes an element from the front (head) of the collection
A doubly linked list has O(1) insertion and deletion at both ends, so it is a natural choice for queues.
Advantages:
- Dynamic size
- Orders data in the order it was received
- Low runtime
Disadvantages
- Can only retrieve the oldest element

3. Linked List
Linked lists are a data structure which, unlike the previous three, does not use physical placement of data in memory. This means that, rather than indexes or positions, linked lists use a referencing system: elements are stored in nodes that contain a pointer to the next node, repeating until all nodes are linked.
This system allows efficient insertion and removal of items without the need for reorganization.
Advantages. (A singly linked list is an ideal data structure to implement a stack. When using a single linked list, the head of the list functions as the top, which contains a reference to the next element (if there is one), and push and pop modify the top of the stack alone. Consequently, stacks are super efficient because most operations are O(1) in time.)
- Efficient insertion and removal of new elements
- Less complex than restructuring an array
Disadvantages
- Uses more memory than arrays
- Inefficient to retrieve a specific element
- Inefficient to traverse the list backward

4. Trees
Trees are another relation-based data structure, which specialize in representing hierarchical structures. Like a linked list, nodes contain both elements of data and pointers marking its relation to immediate nodes.
Each tree has a “root” node, off of which all other nodes branch. The root contains references to all elements directly below it, which are known as its “child nodes”. This continues, with each child node, branching off into more child nodes.
a binary search tree is also called an ordered or sorted binary tree, because it is a rooted binary tree data structure whereby each root node stores a key greater than all the keys in the node's left subtree and less than those in its right subtree.
Nodes with linked child nodes are called internal nodes while those without child nodes are external nodes. A common type of tree is the “binary search tree” which is used to easily search stored data.
These search operations are highly efficient, as its search duration is dependent not on the number of nodes but on the number of levels down the tree.
This type of tree is defined by four strict rules:
1. The left subtree contains only nodes with elements lesser than the root.
2. The right subtree contains only nodes with elements greater than the root.
3. Left and right subtrees must also be a binary search tree. They must follow the above rules with the “root” of their tree.
4. There can be no duplicate nodes, i.e. no two nodes can have the same value.

Advantages

- Ideal for storing hierarchical relationships
- Dynamic size
- Quick at insert and delete operations
- In a binary search tree, inserted nodes are sequenced immediately.
- Binary search trees are efficient at searches; length is only O(height)
O(height)

Disadvantages
- Slow to rearrange nodes
- Child nodes hold no information about their parent node
- Binary search trees are not as fast as the more complicated hash table
- Binary search trees can degenerate into linear search (scanning all elements) if not implemented with balanced subtrees.

5. Graphs
Graphs are a relation-based data structure helpful for storing web-like relationships. Each node, or vertex, as they’re called in graphs, has a title (A, B, C, etc.), a value contained within, and a list of links (called edges) it has with other vertices.

Advantages
- Can quickly convey visuals over text
- Usable to model a diverse number of subjects so long as they contain a relational structure

Disadvantages
- At a higher level, text can be time-consuming to convert to an image.
- It can be difficult to see the existing edges or how many edges a given vertex has connected to it

6. Hash Tables (Map)
Hash tables are a complex data structure capable of storing large amounts of information and retrieving specific elements efficiently. This data structure relies on the concept of key/value pairs, where the “key” is a searched string and the “value” is the data paired with that key.
Each searched key is converted from its string form into a numerical value, called a hash, using a predefined hash function. This hash then points to a storage bucket – a smaller subgroup within the table. It then searches the bucket for the originally entered key and returns the value associated with that key.
Advantages
- Key can be in any form, while array’s indices must be integers
- Highly efficient search function
- Constant number of operations for each search
- Constant cost for insertion or deletion operations
Disadvantages
- Collisions: an error caused when two keys convert to the same hash code or two hash codes point to the same value.
- These errors can be common and often require an overhaul of the hash function.

> Trees connect parents to multiple child nodes as opposed to linked lists, which connects one parent with one child. Graphs allow for the connection of multiple parent nodes to multiple child nodes.

# Keyed collections
1. Maps
A Map object is a simple key/value map and can iterate its elements in insertion order.(a native type for hash tables)
(check CS-list Repo for more info)
