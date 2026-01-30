## Data Structures :
It is the organising and storing the data in sequential order so that it can be used efficiently(Time complexity and space complexity).

#### Time and space complexity : It is measurement of "how much time or space" occupied by an algorithm. 
###### Time Complexity : 
It is very important when consider large or huge data.
Lower the complexity more efficient is the code
It is usually measured by "BIG O".
i.e, O(1),O(n),O(n^2),etc...
For example : Linear search - O(n)
Binary search - O(logn)
##### *O(n) increases linearly , it is faster than O(n^2), slower than O(logn),very much lower than O(2^n)[exponential growth].
<img width="1696" height="941" alt="Screenshot 2026-01-24 173208" src="https://github.com/user-attachments/assets/dc513c46-ba77-4f84-a6a9-e55c1fcaf6c8" />
##### Space Complexity : 
It is very important when consider large or huge data.
Lower the complexity more efficient is the code

##### Classification ->
1. Primitive DS ---- Arrays,Pointers,int,char,double,float,complex
2. Non-Primitive DS  ----  Linear,Non-linear

Linear DS : Stacks,Queues,Linked list etc...
Non-Lonear DS : Trees and Graphs.

##### Operations in DS : 
 1. Initialisation : Initialising some values.
 2. Insertion :  Inserting some values.
 3. Deletion : Deleting some values.
 4. Searching : Searchimg for a particular element or value.
 5. Traversing : Going through each element from first to last.
 6. Sorting : Sorting the values in required order.

#### Stacks:
Works on the principle of "LIFO"(Last in first out) or "FILO"(First in last out).
Can be accesed in a restricted way.
###### Operations :
1. pop() - deletes/pops an element from the stack.
2. push() - adds/pushes an element to the stack.
3. peek() - checks the top element of the stack.
4. isempty() - checks whether the stack is empty or not.
5. isfull() - checks whether the stack is full or not.

##### Applications :
1. Reverse of string
2. Undo and Redo operations
3. Recursion
4. to check the balance of paranthesis/brackects
5. infix to postfix/prefix conversion etc...

#### Linked list :
Elements are not stored in continuos memory location.
Drawback of linked list here is, since all the elements are not stored together after every element a "node" is created which stores the address of next element,hence more space is required.
The last element node contains "null".
Only sequencial accessing is possible i.e O(n).
Insertion and deletion is easily.
Binary search not possible.
Dynamic allocation.

##### Types : 
1. Singly LL: Most commonly used LL , it has two parts one contains element and the othe contains the pointer part.
It has only single list.Can only traverse in forward direction.
Syntax:
stuct node{
int data;
struct node *next;
};

2. Doubly LL:It has three parts one element and two parts contains pointers(pointer to its previous node and next node).
Traversing can be dine from both sides (front and back).
Syntax:
struct node {
int data;
struct node *next;
struct node *previous;
};

3. Circular LL:A variation of singly linked list,here the pointer in the last node contains the address of the first node instead of "null".

4. Doubly Circular LL:Has the properties of both doubly and cicular linked list.

#### ARRAYS VS LINKED LISTS : 
________________________________________________________________
######          ARRAYS             |          LINLED LISTS     |
________________________________________________________________
1. Cost of accessing an element :  |                           |
          O(1)                     |       O(n)                |
2. Memory utilisation :            |                           |
          in-efficient             |      very efficient       |
3. Memory Reqiurement :            |                           |
          less                     |         high              |
4. Cost of insertion :             |                           |
                                   |                           |
--> at begining :    O(n)          |         O(1)              |
--> in middle :      O(1)          |         O(n)              | 
-->at the end :      O(n)          |         O(n)              |    
                                   |                           |
6. Searching :                     |                           |
     Linear & Binary               |         Only linear       |
________________________________________________________________
jdfbjk sdnckj
dsjfkj vljndvjern 
