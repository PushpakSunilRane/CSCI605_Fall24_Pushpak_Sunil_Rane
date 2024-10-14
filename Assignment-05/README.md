# CSCI605
Binary Search Tree (BST) Implementation.
___________________________________________________________________________________________________________________________________________
Binary Search Tree performs four operations :-
    1. Insertion of node
    2. Inorder Traversal
    3. Search node using name
    4. Delete node
__________________________________________________________________________________________________________________________________________
Initially, created TreeNode class to represent node in the BST.Each node contains following :
    1. key: variable used to store name of the person.

    2. value: variable used to store phone-number of the person in key variable.

    3. left: reference to the left child node of the tree. Stores key-value smaller than current node.

    4. right: reference to the right child node of the tree. Stores key-value greater than current node.
__________________________________________________________________________________________________________________________________________
Then, created BinarySearchTree class which is used to perform operations on the tree such as insert, delete, inorder-traversal, delete operations.

Methods:

    1. __init__(self) used to initialize tree with root to None, i.e. empty tree.

    2. insert(self,key,value) used to insert new nodes with key-value (name,phone-number).

    3. inorder_traversal(self) performs the inorder traversal of the tree where it visits nodes in ascending order and returns all the key-value pairs in a sorted list of tuples in result[]

    4. search(self, key) performs the searching of the node from the tree using key provided during call of the function search. If the key isn't found then it returns a message "No records found in the database."

    5. delete(self,node,key) performs deletion of a node from tree where it handles 3 cases for node deletion.
        a. Deleting node with no child
        b. Deleting node with one child
        c. Deleting node with two child

    6. minValueNode(self,node) is helper function used in delete method. It finds the node with smallest key in the right subtree.
__________________________________________________________________________________________________________________________________________
Then, creating a object for BinarySearchTree class to call methods inside that class.

    1. bst.insert(key,value) used to insert the nodes in the BST.2. bst.search(key) used to search node in the tree with the help of key provided during call of function to search matching key. If not found, prints message "No record found in the database."
    2. bst.inorder_traversal() performs traversal and returns sorted key-value pairs in list of tupels in result[]
    3. bst.delete(bst.root,key) performs delete operation calling the delete function finds the key and according to that deletes the node from the tree
_________________________________________________________________________________________________________________________________________