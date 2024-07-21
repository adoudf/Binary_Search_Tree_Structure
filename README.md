## Binary Search Tree  README

To compile: make all
To Execute: make run

Utilizing Struct called BSTNode to preform BST Opperartion

insert Function:
This function inserts a new node with value val into the BST.
- If the root is NULL, it creates a new node and returns it.
- Otherwise, it recursively calls itself to insert the node in the correct position.

initializeBalance Function:
This function initializes the balance by inserting all elements from the input array arr into the BST.
- It creates a new node with the first element of the array and then iterates through the rest of the elements, inserting them into the BST.

kSmallest Function:
This function finds the k-th smallest element in the BST.
- It recursively traverses the left subtree, then checks the current node, and finally, recursively traverses the right subtree.

inorderTraversal Function:
This function performs an inorder traversal of the BST and prints the node values.

Main Function:
- It initializes an array arr.
- It initializes a variable k to get the user's input for the k-th smallest element.
- It initializes a variable count to keep track of the number of nodes visited during the search.
- It initializes the BST using initializeBalance.
- It prints the inorder traversal of the BST.
- It asks the user to input the value of k.
- It calls the kSmallest function to find the k-th smallest element.
- It prints the k-th smallest element.




