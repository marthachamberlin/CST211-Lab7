# CST211-Lab7
Lab 7
Binary Search Tree
Description
Create a Binary Search Tree ADT as discussed in class.
Stipulations
You will need to create your own class diagram including the correct relationship. This must be submitted with your program. I suggest you use Dia.
You must include the following functions.
* Insert
* Delete
* Purge
* Height
* InOrder Traversal
* PreOrder Traversal
* PostOrder Traversal
* BreadthFirst Traversal
* Appropriate Manager Functions

All traversal functions must accept a function pointer to the visit function to be called. See the example below.
1 //BSTree method 
2 void BSTree::InOrder(BSNode* root, void (*visit)(T data))
3 {
4 }
5 //Consumer function
6 void Display(int data)
7 {
8 	cout << data << endl;
9 }

1 //Consumer call to the InOrder traversal
2 bst.InOrder(Display);

Deliverables

One file including:
* Your code
* Your test(s) similar to Lab1_test.cpp & Lab2_test.cpp and their results
