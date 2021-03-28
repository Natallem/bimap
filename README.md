# bimap
Bimap is a data structure that stores a set of pairs and efficiently searches for a key by value. Unlike map, bimap searches can be performed both on the left (left) elements of the pairs, and on the right (right).

Bimap is parameterized by 2 types (left and right) and 2 comparators that determine the order of these types.

The behavior of bimap iterators is the same as map iterators and allow traverse elements in both left and right side in the order specified by the passed comparators.

## Performance 
 * Inserting, deleting, searching elements of both left and right types in O(logn)
 * Minimum number of memory allocations (one memory allocation for one bimap element)
 * No memory allocations in empty bimap
