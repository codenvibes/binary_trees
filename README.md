<h1 align="center"><b>0x1D. C - BINARY TREES</b></h1>
<div align="center"><code>C</code> <code>Group project</code> <code>Algorithm</code> <code>Data structure</code></div>

<!-- # Background Context -->

# Resources
<details>
<summary><b><a href="https://en.wikipedia.org/wiki/Binary_tree">Binary tree</a></b> (note the first line: <code>Not to be confused with B-tree.</code>)</summary><br>


<br><p align="center">※※※※※※※※※※※※</p><br>
</details>

<details>
<summary><b><a href="https://www.tutorialspoint.com/data_structures_algorithms/tree_data_structure.htm">Data Structure and Algorithms - Tree</a></b></summary><br>


<br><p align="center">※※※※※※※※※※※※</p><br>
</details>

<details>
<summary><b><a href="https://www.programiz.com/dsa/tree-traversal">Tree Traversal</a></b></summary><br>


<br><p align="center">※※※※※※※※※※※※</p><br>
</details>

<details>
<summary><b><a href="https://en.wikipedia.org/wiki/Binary_search_tree">Binary Search Tree</a></b></summary><br>


<br><p align="center">※※※※※※※※※※※※</p><br>
</details>

<details>
<summary><b><a href="https://www.youtube.com/watch?v=H5JubkIy_p8">Data structures: Binary Tree</a></b></summary><br>


<br><p align="center">※※※※※※※※※※※※</p><br>
</details>


<!-- **man or help:**
- `` -->

# Learning Objectives
<details>
<summary><b><a href=" "> </a>What is a binary tree</b></summary><br>


<br><p align="center">※※※※※※※※※※※※</p><br>
</details>

<details>
<summary><b><a href=" "> </a>What is the difference between a binary tree and a Binary Search Tree</b></summary><br>


<br><p align="center">※※※※※※※※※※※※</p><br>
</details>

<details>
<summary><b><a href=" "> </a>What is the possible gain in terms of time complexity compared to linked lists</b></summary><br>


<br><p align="center">※※※※※※※※※※※※</p><br>
</details>

<details>
<summary><b><a href=" "> </a>What are the depth, the height, the size of a binary tree</b></summary><br>


<br><p align="center">※※※※※※※※※※※※</p><br>
</details>

<details>
<summary><b><a href=" "> </a>What are the different traversal methods to go through a binary tree</b></summary><br>


<br><p align="center">※※※※※※※※※※※※</p><br>
</details>

<details>
<summary><b><a href=" "> </a>What is a complete, a full, a perfect, a balanced binary tree</b></summary><br>


<br><p align="center">※※※※※※※※※※※※</p><br>
</details>

# Requirements

### General
- Allowed editors: `vi`, `vim`, `emacs`
- All your files will be compiled on Ubuntu 20.04 LTS using gcc, using the options -Wall -Werror -Wextra -pedantic -std=gnu89
- All your files should end with a new line
- A `README.md` file, at the root of the folder of the project, is mandatory
- Your code should use the `Betty` style. It will be checked using [betty-style.pl](https://github.com/alx-tools/Betty/blob/master/betty-style.pl) and [betty-doc.pl](https://github.com/alx-tools/Betty/blob/master/betty-doc.pl)
- You are not allowed to use global variables
- No more than 5 functions per file
- You are allowed to use the standard library
- In the following examples, the `main.c` files are shown as examples. You can use them to test your functions, but you don’t have to push them to your repo (if you do we won’t take them into account). We will use our own `main.`c files at compilation. Our `main.c` files might be different from the one shown in the examples
- The prototypes of all your functions should be included in your header file called `binary_trees.h`
- Don’t forget to push your header file
- All your header files should be include guarded

### GitHub
**There should be one project repository per group. If you clone/fork/whatever a project repository with the same name before the second deadline, you risk a 0% score.**

# More Info
<details>
<summary><h3>Data structures</h3></summary>

Please use the following data structures and types for binary trees. Don’t forget to include them in your header file.

### Basic Binary Tree
```c
/**
 * struct binary_tree_s - Binary tree node
 *
 * @n: Integer stored in the node
 * @parent: Pointer to the parent node
 * @left: Pointer to the left child node
 * @right: Pointer to the right child node
 */
struct binary_tree_s
{
    int n;
    struct binary_tree_s *parent;
    struct binary_tree_s *left;
    struct binary_tree_s *right;
};

typedef struct binary_tree_s binary_tree_t;
```
### Binary Search Tree
```c
typedef struct binary_tree_s bst_t;
```
### AVL Tree
```c
typedef struct binary_tree_s avl_t;
```
### Max Binary Heap
```c
typedef struct binary_tree_s heap_t;
```
**Note**: For tasks 0 to 23 (included), you have to deal with simple binary trees. They are not BSTs, thus they don’t follow any kind of rule.
</details>

<details>
<summary><h3>Print function</h3></summary>

To match the examples in the tasks, you are given [this function](https://github.com/alx-tools/0x1C.c)

This function is used only for visualization purposes. You don’t have to push it to your repo. It may not be used during the correction
</details>


# Tasks
<details>
<summary>

### 0. New node
`mandatory`

File: [0-binary_tree_node.c]()
</summary>


</details>

<details>
<summary>

### 1. Insert left
`mandatory`

File: [1-binary_tree_insert_left.c]()
</summary>


</details>

<details>
<summary>

### 2. Insert right
`mandatory`

File: [2-binary_tree_insert_right.c]()
</summary>


</details>

<details>
<summary>

### 3. Delete
`mandatory`

File: [3-binary_tree_delete.c]()
</summary>


</details>

<details>
<summary>

### 4. Is leaf
`mandatory`

File: [4-binary_tree_is_leaf.c]()
</summary>


</details>

<details>
<summary>

### 5. Is root
`mandatory`

File: [5-binary_tree_is_root.c]()
</summary>


</details>

<details>
<summary>

### 6. Pre-order traversal
`mandatory`

File: [6-binary_tree_preorder.c]()
</summary>


</details>

<details>
<summary>

### 7. In-order traversal
`mandatory`

File: [7-binary_tree_inorder.c]()
</summary>


</details>

<details>
<summary>

### 8. Post-order traversal
`mandatory`

File: [8-binary_tree_postorder.c]()
</summary>


</details>

<details>
<summary>

### 9. Height
`mandatory`

File: [9-binary_tree_height.c]()
</summary>


</details>

<details>
<summary>

### 10. Depth
`mandatory`

File: [10-binary_tree_depth.c]()
</summary>


</details>

<details>
<summary>

### 11. Size
`mandatory`

File: [11-binary_tree_size.c]()
</summary>


</details>

<details>
<summary>

### 12. Leaves
`mandatory`

File: [12-binary_tree_leaves.c]()
</summary>


</details>

<details>
<summary>

### 13. Nodes
`mandatory`

File: [13-binary_tree_nodes.c]()
</summary>


</details>

<details>
<summary>

### 14. Balance factor
`mandatory`

File: [14-binary_tree_balance.c]()
</summary>


</details>

<details>
<summary>

### 15. Is full
`mandatory`

File: [15-binary_tree_is_full.c]()
</summary>


</details>

<details>
<summary>

### 16. Is perfect
`mandatory`

File: [16-binary_tree_is_perfect.c]()
</summary>


</details>

<details>
<summary>

### 17. Sibling
`mandatory`

File: [17-binary_tree_sibling.c]()
</summary>


</details>

<details>
<summary>

### 18. Uncle
`mandatory`

File: [18-binary_tree_uncle.c]()
</summary>


</details>

<details>
<summary>

### 19. Lowest common ancestor
`#advanced`

File: [100-binary_trees_ancestor.c]()
</summary>


</details>

<details>
<summary>

### 20. Level-order traversal
`#advanced`

File: [101-binary_tree_levelorder.c]()
</summary>


</details>

<details>
<summary>

### 21. Is complete
`#advanced`

File: [102-binary_tree_is_complete.c]()
</summary>


</details>

<details>
<summary>

### 22. Rotate left
`#advanced`

File: [103-binary_tree_rotate_left.c]()
</summary>


</details>

<details>
<summary>

### 23. Rotate right
`#advanced`

File: [104-binary_tree_rotate_right.c]()
</summary>


</details>

<details>
<summary>

### 24. Is BST
`#advanced`

File: [110-binary_tree_is_bst.c]()
</summary>


</details>

<details>
<summary>

### 25. BST - Insert
`#advanced`

File: [111-bst_insert.c](), [0-binary_tree_node.c]()
</summary>


</details>

<details>
<summary>

### 26. BST - Array to BST
`#advanced`

File: [112-array_to_bst.c](), [111-bst_insert.c](), [0-binary_tree_node.c]()
</summary>


</details>

<details>
<summary>

### 27. BST - Search
`#advanced`

File: [113-bst_search.c]()
</summary>


</details>

<details>
<summary>

### 28. BST - Remove
`#advanced`

File: [114-bst_remove.c]()
</summary>


</details>

<details>
<summary>

### 29. Big O #BST
`#advanced`

File: [115-O]()
</summary>


</details>

<details>
<summary>

### 30. Is AVL
`#advanced`

File: [120-binary_tree_is_avl.c]()
</summary>


</details>

<details>
<summary>

### 31. AVL - Insert
`#advanced`

File: [121-avl_insert.c](), [14-binary_tree_balance.c](), [103-binary_tree_rotate_left.c](), [104-binary_tree_rotate_right.c](), [0-binary_tree_node.c]()
</summary>


</details>

<details>
<summary>

### 32. AVL - Array to AVL
`#advanced`

File: [122-array_to_avl.c](), [121-avl_insert.c](), [0-binary_tree_node.c](), [103-binary_tree_rotate_left.c](), [104-binary_tree_rotate_right.c](), [14-binary_tree_balance.c]()
</summary>


</details>

<details>
<summary>

### 33. AVL - Remove
`#advanced`

File: [123-avl_remove.c](), [14-binary_tree_balance.c](), [103-binary_tree_rotate_left.c](), [104-binary_tree_rotate_right.c]()
</summary>


</details>

<details>
<summary>

### 34. AVL - From sorted array
`#advanced`

File: [124-sorted_array_to_avl.c](), [0-binary_tree_node.c]()
</summary>


</details>

<details>
<summary>

### 35. Big O #AVL Tree
`#advanced`

File: [125-O]()
</summary>


</details>

<details>
<summary>

### 36. Is Binary heap
`#advanced`

File: [130-binary_tree_is_heap.c]()
</summary>


</details>

<details>
<summary>

### 37. Heap - Insert
`#advanced`

File: [131-heap_insert.c](), [0-binary_tree_node.c]()
</summary>


</details>

<details>
<summary>

### 38. Heap - Array to Binary Heap
`#advanced`

File: [132-array_to_heap.c](), [131-heap_insert.c](), [0-binary_tree_node.c]()
</summary>


</details>

<details>
<summary>

### 39. Heap - Extract
`#advanced`

File: [133-heap_extract.c]()
</summary>


</details>

<details>
<summary>

### 40. Heap - Sort
`#advanced`

File: [134-heap_to_sorted_array.c](), [133-heap_extract.c]()
</summary>


</details>

<details>
<summary>

### 41. Big O #Binary Heap
`#advanced`

File: [135-O]()
</summary>


</details>

