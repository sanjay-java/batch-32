#### What is the difference between List and set

      The main difference between the List and Set interface in Java is that List allows duplicates while Set doesn't allow duplicates. All implementation of Set honor this contract.

      Lists maintains insertion order of elements. Set is an unordered collection, you get no guarantee on which order element will be stored.

#### Difference between HashSet vs TreeSet
      HashSet is Implemented using a hash table. Elements are not ordered. Where as, TreeSet is implemented using a tree structure. The elements in a set are sorted.

      HashSet is faster than TreeSet and should be preferred choice if sorting of element is not required.

      HashSet allows null object but TreeSet doesn't allow null Object and throw NullPointerException
