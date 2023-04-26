# Stack

A stack is a linear data structure, a collection of items of the same type. In a stack, the insertion and deletion of elements happen only at one endpoint. The behavior of a stack is described as “Last In, First Out” (LIFO). When an element is “pushed” onto the stack, it becomes the first item that will be “popped” out of the stack.

# About the code
3 separate functions have been declared to perform the push, pop operations and to display the elements of the stack.

# Variables Used
Global Variables  
"int stk[10]" array of int type and size=10 to store elements of the stack.  
"int top" to store the topmost element of the stack.  
"int data" to input data entered and store it in the stack.  

Inside the main  
"int choice" to store the choice of the user.  

Inside function void display()  
"int i" for running iteration on the for loop.

# Functions
void push(int data)  
To push the data entered into the stack.  
If stack is full the program gives a message "Stack Overflow" Otherwise it adds the element to the top of the stack.

void pop()  
If the value of top=-1, that is, if the stack is empty the program gives a message "Stack Underflow".Otherwise it pops the element from the stack.

void display()  
If the value of top=-1, that is, if the stack is empty the program gives a message "Stack is Empty".Otherwise displays the elemnts present in stack from top to bottom

![image](https://cdn.programiz.com/sites/tutorial2program/files/stack.png)
