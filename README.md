# 0x1D. C - Binary trees

## Resources
#### Read or watch:

- [Binary tree (*note the first line: Not to be confused with B-tree.*)](https://alx-intranet.hbtn.io/rltoken/1F2x42-8vUbOmU4L1C1KMg)
- [Data Structure and Algorithms - Tree](https://alx-intranet.hbtn.io/rltoken/QmcTMCkQyrgMjrqoWxYdhw)
- [Tree Traversal](https://alx-intranet.hbtn.io/rltoken/nMxoYQdZR_guroan8JeqBQ)
- [Binary Search Tree](https://alx-intranet.hbtn.io/rltoken/qO5dBlMnYJzbaWG3xVpcnQ)
- [Data structures: Binary Tree](https://alx-intranet.hbtn.io/rltoken/BeyJ2gjlE7_djwRiDyeHig)


## GitHub
**There should be one project repository per group. If you clone/fork/whatever a project repository with the same name before the second deadline, you risk a 0% score.**

## More Info
### Data structures
Please use the following data structures and types for binary trees. Don’t forget to include them in your header file.

#### Basic Binary Tree

> /**
> * struct binary_tree_s - Binary tree node
> *
> * @n: Integer stored in the node
> * @parent: Pointer to the parent node
> * @left: Pointer to the left child node
> * @right: Pointer to the right child node
> */
> struct binary_tree_s
> {
>    int n;
>    struct binary_tree_s *parent;
>    struct binary_tree_s *left;
>    struct binary_tree_s *right;
> };
>
> typedef struct binary_tree_s binary_tree_t;

### Binary Search Tree

> typedef struct binary_tree_s bst_t;

### AVL Tree
> typedef struct binary_tree_s avl_t;

### Max Binary Heap
> typedef struct binary_tree_s heap_t;

*Note*: For tasks 0 to 23 (included), you have to deal with simple binary trees. They are not BSTs, thus they don’t follow any kind of rule.

### Print function

- To match the examples in the tasks, you are given [this function](https://github.com/holbertonschool/0x1C.c)

- This function is used only for visualization purposes. You don’t have to push it to your repo. It may not be used during the correction