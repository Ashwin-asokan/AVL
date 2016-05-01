# AVL
AVL Tree Implementation
GitHub link: https://github.com/Ashwin-asokan/AVL

Usage Setup Instructions:
Checkout avl.py into the project
Import avl into the file to be used

example usage:

tree = avl.node(5)
tree = tree.insert(8).insert(4)
print tree.inOrder()
tree = tree.delete(4)
print tree.inOrder()

Refer test_avl.py for further usage examples.

performance plot can be run directly
1. Search -> search_time_test.py
2. Insertion -> insertion_time_test.py
3. Deletion -> deletion_time_test.py

No params just python search_time_test.py to obtain the plot.
