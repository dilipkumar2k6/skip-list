# Write code
https://leetcode.com/problems/design-skiplist/
# Summary
- Skip list is a probabilistic search structure
- Like BST, skip list is designed to to overcome the basic limitation of array or linked list
- Skip list is example of probabilistic data structure because it makes some of its decisions at random
- Skip list provides alternative to BST and related to tree structure
- The primary problem with BST is that it may easily become unbalanced
- The `2-3` tree is guaranteed to remain balanced regardless of the order in which data is values are inserted, but it is rather complicated to implement. 
- The `AVL Tree` and `Splay Tree` are also guaranteed to provide good performance, but at the cost of added complexity as compare to BST
- Skip list is easier to implement than known balanced tree structure.
- The skip list is not guaranteed to provide good performance (O logn)
- But it provides good performance with extremely high probability 
- As such, it represents a good compromise between difficulties of implementation and performance. 
# Search, insertion and deletion
https://www.youtube.com/watch?v=Q9MdwzewSZg  
# Reference 
https://opendsa-server.cs.vt.edu/ODSA/Books/CS3/html/SkipList.html