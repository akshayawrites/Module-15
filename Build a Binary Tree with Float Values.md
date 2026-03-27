# Ex. No: 15A - Build a Binary Tree with Float Values

## AIM:
To write a Python program to build a binary tree with a root, left, and right node using floating-point values.

---

## ALGORITHM:

1. **Start the program.**
2. **Import** the `Node` class from the `binarytree` module.
3. **Create a root node** using the `Node` class and assign a floating-point value.
4. **Create left and right child nodes** for the root with float values.
5. **Convert the tree** to a list and print the list of nodes.
6. **End the program.**

---

## PYTHON PROGRAM

```
from binarytree import build,Node

def bst(x):
    if len(x)==0:
        return None
    
    mid = len(x)//2
    root=Node(x[mid])
    root.left=bst(x[:mid])
    root.right=bst(x[mid+1:])
    return root 


l=[1,2,3,5,4,6]

print("BST before insertion:")
xbst=bst(sorted(l))
for i in xbst.values:
    print(i,"-->",end="")
    
print()
print("BST after insertion:")
l.append(int(input()))
xbst=bst(sorted(l))
for i in xbst.values:
    print(i,"-->",end="")
```
## OUTPUT
```
<img width="1185" height="270" alt="image" src="https://github.com/user-attachments/assets/0c35bc5a-8bd5-489a-8f6e-514d47f04f6e" />

```
## RESULT
Thus, the Python program to print a binary tree consisting of a root, left, and right node has been implemented and executed successfully.
