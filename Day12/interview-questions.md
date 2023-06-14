#### What is the difference between Process and Thread?
    A process is a self contained execution environment and it can be seen as a program or application whereas Thread is a single task of execution within the process. Java runtime environment runs as a single process which contains different classes and programs as processes. Thread can be called lightweight process. Thread requires less resources to create and exists in the process, thread shares the process resources.


#### How can we create a Thread in Java?
    There are two ways to create Thread in Java - first by implementing Runnable interface and then creating a Thread object from it and second is to extend the Thread Class.

#### Can we call run() method of a Thread class?  
    Yes, we can call run() method of a Thread class but then it will behave like a normal method. To actually execute it in a Thread, we need to start it using **start()** method.

#### What are different states in lifecycle of Thread?
    When we create a Thread in java program, its state is New. Then we start the thread that change it's state to Runnable. Thread Scheduler is responsible to allocate CPU to threads in Runnable thread pool and change their state to Running. Other Thread states are Waiting, Blocked and Dead.
