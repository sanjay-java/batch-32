#### Abstraction
    Abstraction is the process of separating ideas from specific instances and thus, develop classes in terms of their own functionality, instead of their implementation details. Java supports the creation and existence of abstract classes that expose interfaces, without including the actual implementation of all methods. The abstraction technique aims to separate the implementation details of a class from its behavior.

####  What is Encapsulation
    Encapsulation provides objects with the ability to hide their internal characteristics and behavior.
    Some of the advantages of using encapsulation are listed below:
      The internal state of every objected is protected by hiding its attributes.
      It increases usability and maintenance of code, because the behavior of an object can be independently changed or extended.
      It improves modularity by preventing objects to interact with each other, in an undesired way.

####  What is Polymorphism
      Polymorphism is the ability of an object to take on many forms.
      Compile Time Polymorphism - is a process in which an overloaded method is resolved at compile time.
      Runtime Polymorphism - is a process in which a call to an overridden method is resolved at runtime rather than compile-time


#### Differences between Abstraction and Encapsulation
    Abstraction and encapsulation are complementary concepts. On the one hand, abstraction focuses on the behavior of an object. On the other hand, encapsulation focuses on the implementation of an object’s behavior. Encapsulation is usually achieved by hiding information about the internal state of an object and thus, can be seen as a strategy used in order to provide abstraction.

#### Which class is the superclass of all classes?
    java.lang.Object is the root class for all the java classes and we don’t need to extend it.

#### What is an abstract class?
    Abstract classes are used in java to create a class with some default method implementation for subclasses. An abstract class can have an abstract method without the body and it can have methods with implementation also.
    abstract keyword is used to create a abstract class. Abstract classes can’t be instantiated and mostly used to provide base for sub-classes to extend and implement the abstract methods and override or use the implemented methods in abstract class. Read important points about abstract classes at java abstract class.
