# CSCI605
Binary Search Tree (BST) Implementation.
____________________________________________________________________________
Binary Search Tree performs four operations :-
    1. Insertion of node
    2. Inorder Traversal
    3. Search node using name
    4. Delete node
____________________________________________________________________________
Initially, created TreeNode class to represent node in the BST.Each node contains following :
    1. key: variable used to store name of the person.
    2. value: variable used to store phone-number of the person in key variable.
    3. left: reference to the left child node of the tree. Stores key-value smaller than current node.
    4. right: reference to the right child node of the tree. Stores key-value greater than current node.
____________________________________________________________________________
Then, created BinarySearchTree class which is used to perform operations on the tree such as insert, delete, inorder-traversal, delete operations.

    Methods:
        1. __init__(self) used to initialize tree with root to None, i.e. empty tree.

        2. insert(self,key,value) used to insert new nodes with key-value (name,phone-number).

        3. 

_____________________________________________________________________________
then performing calculations as per selection of operation number :-
    if operation number = 1 then
        perform addition,display result and ask whether to continue or exit.
    if operation number = 2 then
        perform substraction,display result and ask whether to continue or exit.
    if operation number = 3 then
        perform multiplication,display result and ask whether to continue or exit.
    if operation number = 4 then
        if num2 = 0 then 
            print("Division Error.")
        else
            perform division,display result and ask whether to continue or exit.
_______________________________________________________________________________
Choose to continue or exit operations -:
    if calc = Y then
        start from initial step from entering operation to perform.
    if calc != Y then
        print("Calculator Shutdown Successfully") and break loop to exit from program.
________________________________________________________________________________