#### What is a functional interface in Java?

   A functional interface in Java is an interface that contains exactly one abstract method. It serves as the basis for lambda expressions and functional programming in Java.

#### What is the purpose of the @FunctionalInterface annotation in Java?

   The @FunctionalInterface annotation is used to indicate that an interface is intended to be a functional interface. It helps in detecting and preventing accidental addition of extra abstract methods in the interface.

#### What is a lambda expression in Java? How is it related to functional interfaces?

   A lambda expression in Java is a concise representation of an anonymous function that can be passed around as a value. It is closely related to functional interfaces because a lambda expression can be used to provide the implementation of the single abstract method in a functional interface.

#### How do you define a lambda expression in Java?

   A lambda expression in Java is defined using the following syntax: (parameters) -> expression. It consists of a comma-separated list of parameters, followed by an arrow (->) and an expression or a block of statements.

#### What are the advantages of using lambda expressions in Java?

   The advantages of using lambda expressions in Java include shorter and more readable code, improved code maintainability, and the ability to express behavior directly at the point of use without the need for additional classes or anonymous inner classes.

#### What are the built-in functional interfaces in the java.util.function package?

   The java.util.function package in Java provides several built-in functional interfaces, including Predicate, Function, Consumer, Supplier, UnaryOperator, and BinaryOperator. These interfaces represent common functional patterns and can be used directly or combined to create more complex behaviors.

#### What is the difference between a functional interface and a regular interface in Java?

   The main difference is that a functional interface must have exactly one abstract method, known as the functional method. In contrast, a regular interface can have any number of abstract methods.

#### Can a functional interface have multiple abstract methods?

   No, a functional interface cannot have multiple abstract methods. The whole purpose of a functional interface is to have a single abstract method that represents a specific behavior or operation.

#### What are streams in Java?

    Streams in Java provide a declarative way to process collections of data in a functional programming style. They allow for efficient and concise operations on data, such as filtering, mapping, and reducing.

#### What are intermediate operations in streams?

    Intermediate operations in streams are operations that can be chained together to transform or filter the stream. Examples include filter(), map(), sorted(), and distinct().

#### What are terminal operations in streams?

    Terminal operations in streams are operations that produce a result or a side effect. Examples include forEach(), collect(), reduce(), and count().

#### What is the difference between intermediate and terminal operations in streams?

    Intermediate operations are lazy and do not produce a result until a terminal operation is encountered. Terminal operations trigger the processing of the stream and produce a final result or side effect.

#### What is the difference between the forEach() method and the collect() method in streams?

    The forEach() method performs an operation on each element of the stream without returning a result. The collect() method accumulates the elements of the stream into a collection or a single value and returns the result.
