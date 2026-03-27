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
ENTER YOUR CODE
from binarytree import Node
l = []
for i in range(3):
l.append(input())
root = Node(l[0])
root.left = Node(l[1])
root.right = Node(l[2])
print("Binary Tree : ")
for i in root.values:
print(i, "--> ", end="")
```
## OUTPUT
```
<img width="564" height="252" alt="image" src="https://github.com/user-attachments/assets/ee293bc5-d264-4ca9-9730-fbb28464758d" />
```
## RESULT
Thus, the Python program to print a binary tree consisting of a root, left, and right node has been implemented and executed successfully.
