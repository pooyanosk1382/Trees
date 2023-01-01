# Trees
Code of binary tree, fenwick tree, redblack tree, BTree and AVL tree in python
These codes can be useful for analysis data and save them in a good way and have a conviniet access to data.

# Binary tree
In computer science, a binary tree is a k-ary k = 2 k=2 tree data structure in which each node has at most two children, which are referred to as the left child and the right child. A recursive definition using just set theory notions is that a (non-empty) binary tree is a tuple (L, S, R), where L and R are binary trees or the empty set and S is a singleton set containing the root. Some authors allow the binary tree to be the empty set as well.

# Fenwick tree
A Fenwick tree or binary indexed tree is a data structure that can efficiently update elements and calculate prefix sums in a table of numbers.

This structure was proposed by Boris Ryabko in 1989 with a further modification published in 1992. It has subsequently become known under the name Fenwick tree after Peter Fenwick, who described this structure in his 1994 article.

When compared with a flat array of numbers, the Fenwick tree achieves a much better balance between two operations: element update and prefix sum calculation. A flat array of n n numbers can either store the elements or the prefix sums. In the first case, computing prefix sums requires linear time; in the second case, updating the array elements requires linear time (in both cases, the other operation can be performed in constant time). Fenwick trees allow both operations to be performed in O ( log ⁡ n ) O(\log n) time. This is achieved by representing the numbers as a tree, where the value of each node in the tree is the prefix sum of the array from the index of the parent (inclusive) up to the index of the node (exclusive). The tree must therefore have one more node than the number of elements in the flat array representation. The tree structure allows the operations of element retrieval, element update, prefix sum, and range sum to be performed using only O ( log ⁡ n ) O(\log n) node accesses. 

# Red black tree
In computer science, a red–black tree is a kind of self-balancing binary search tree. Each node stores an extra bit representing "color" ("red" or "black"), used to ensure that the tree remains balanced during insertions and deletions.

When the tree is modified, the new tree is rearranged and "repainted" to restore the coloring properties that constrain how unbalanced the tree can become in the worst case. The properties are designed such that this rearranging and recoloring can be performed efficiently.

The re-balancing is not perfect, but guarantees searching in O ( log ⁡ n ) O(\log n) time, where n n is the number of entries. The insert and delete operations, along with the tree rearrangement and recoloring, are also performed in O ( log ⁡ n ) O(\log n) time.
