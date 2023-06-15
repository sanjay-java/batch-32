#### What is the synchronized keyword used for?

    The synchronized keyword is used in Java to create a synchronized block or method, which ensures that only one thread can access that block or method at a time. It is used for thread synchronization and preventing race conditions.

#### What is the difference between wait() and sleep() methods in Java?

    The wait() method is used to make a thread wait until it is notified by another thread, while the sleep() method pauses the execution of a thread for a specified amount of time.

#### What is a race condition?

    A race condition occurs when multiple threads access shared data concurrently, leading to unpredictable results. It happens when the outcome of the program depends on the relative ordering of thread execution.

#### What is ExecutorService in Java?

  ExecutorService is a higher-level concurrency utility in Java that provides an interface for managing and executing asynchronous tasks. It simplifies the process of executing tasks in the background and managing thread pools.

#### What are the advantages of using ExecutorService over creating threads manually?

    ExecutorService provides several advantages:
      - It manages the lifecycle of threads, reusing them instead of creating new ones for each task, which reduces overhead.
      - It provides a higher level of abstraction, making it easier to manage and control concurrent tasks.
      - It supports various thread pool configurations, such as fixed thread pool, cached thread pool, and scheduled thread pool.

#### What is the difference between execute() and submit() methods in ExecutorService?

      The execute() method is used to submit a Runnable task without expecting any result. It does not return a Future object.
      The submit() method is used to submit a Callable or Runnable task and returns a Future object, which can be used to obtain the result or check the status of the task.
  
