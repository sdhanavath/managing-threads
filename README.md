# Managing threads in Java

In Java, a thread is an independent path of code execution with in a program.Java allows for multiple threads to run at the same time. In other words, multitasking. Here you will learn to create threads, manage threads, synchronize and lock threads, and finally review concurrency utilities available for use with threads. So, let's get started.

## 1. Threads

* Every java program has a default main thread.
* A thread is an independent path of code execution with in a program.
* Many threads can run concurrently in a Java program.
* Threads can be used to perform time-intensive tasks.
* Runnables are objects that encapsulate code sequences.
* Each thread runs a runnable object.
* Threads can initiate an asynchronous object.
* Asynchronous means that it can run concurrently, a the same time instead of sequentially.
* The JVM gives each thread it's own private JVM stack.
* Thread's private JVM stack prevents threads from interfering with each other.
* The JVM stack holds the local variables.
* It also tracks next instructions and calls methods.
* Java supports threads through java.lang.Thread class and java.lang.Runnalbe interface.
* Threads are either daemon or non-daemon threads.
* Daemon threads don't stop the JVM from ending.
* Threads by default are non-daemon threads.
* For example, Java garbage collection runs on a daemon thread.
* A daemon threads is created calling setDaemon(true).
* The java main() method is a non-daemon thread.
* The program ends when the no-daemon threads have died.

### 1.1 How to create thread
 There are two ways to create a thread
* Extend <i>java.lang.Thread</i> class

* Implement Runnable <i> java.lang.Runnable</i> interface



## 2. Synchronization

## 3. Concurrency