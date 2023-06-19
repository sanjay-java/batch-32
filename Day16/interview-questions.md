#### What are the basic interfaces of Java Collections Framework ?
  -  Java Collections Framework provides a well designed set of interfaces and classes that support operations on a collections of objects. The most basic interfaces that reside in the Java Collections Framework are:
  -  Collection, which represents a group of objects known as its elements.
  -  Set, which is a collection that cannot contain duplicate elements.
  -  List, which is an ordered collection and can contain duplicate elements.
  -  Map, which is an object that maps keys to values and cannot contain duplicate keys.

#### What is an Iterator?
  - The Iterator interface provides methods to iterate over any Collection.
  - We can get iterator instance from a Collection using iterator() method. Java Collection iterator provides a generic way for traversal through the elements of a collection.
  - Iterators also allows the caller to remove elements from the underlying collection during the iteration.

#### What are similarities and difference between ArrayList and Vector?
 - similarities
  - Both are index based and backed up by an array internally.
  - Both maintains the order of insertion and we can get the elements in the order of insertion.
  - The iterator implementations of ArrayList and Vector both are fail-fast by design.
  - ArrayList and Vector both allows null values and random access to element using index number.
 - differences
   - Vector is synchronized whereas ArrayList is not synchronized.
   - ArrayList is faster than Vector because it doesn’t have any overhead because of synchronization.

#### What is difference between Array and ArrayList? When will you use Array over ArrayList?
 -   Arrays can contain primitive or Objects whereas ArrayList can contain only Objects.
 - Arrays are fixed-size whereas ArrayList size is dynamic.
 - Arrays don’t provide a lot of features like ArrayList, such as addAll, removeAll, iterator, etc.

 - Although ArrayList is the obvious choice when we work on the list, there are a few times when an array is good to use.

 - If the size of list is fixed and mostly used to store and traverse them.
 - For list of primitive data types, although Collections use autoboxing to reduce the coding effort but still it makes them slow when working on fixed size primitive data types.

#### What is difference between ArrayList and LinkedList?

 - ArrayList and LinkedList both implement List interface but there are some differences between them.

 - ArrayList is an index based data structure backed by Array, so it provides random access to its elements with performance as O(1) but LinkedList stores data as list of nodes where every node is linked to its previous and next node. So even though there is a method to get the element using index, internally it traverse from start to reach at the index node and then return the element, so performance is O(n) that is slower than ArrayList.

 - Insertion, addition or removal of an element is faster in LinkedList compared to ArrayList because there is no concept of resizing array or updating index when element is added in middle.

 - LinkedList consumes more memory than ArrayList because every node in LinkedList stores reference of previous and next elements.
