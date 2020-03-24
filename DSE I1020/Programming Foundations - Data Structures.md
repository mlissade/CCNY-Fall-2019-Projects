# Programming Foundations: Data Structures

## arrays
### pros
- fast access to elements
### cons
- to insert or delete elements, the following elements have to be shifted slowing down computation

## lists
### pros
- to insert or delete elements, the following elements do not have to be shifted
### cons
- accessing could take linear time in the worst case because we need to grab each item to find the next one
- updating also takes O of N time because we need to find the appropriate node and then update its value
- require more memory

## stacks and queues
### pros
- data more easily managed
### cons
- random access not possible

## hash-based data structures (Key-Values)
### pros
- searching is much faster than many other data structures
- insertion and deletion is quick
- runtime is consistent across any input
### cons
- separate chaining takes up O(n) time
- takes up space

## trees
### pros
- maintain sorted order
- fast for insertion, deletion, and accessing
### cons
- unbalanced tress 