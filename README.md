# Java Multithreading Program

## Aim
To create multiple threads in Java using:
1. Extending the `Thread` class.
2. Implementing the `Runnable` interface.

## Problem Statement
Write a Java program in which:
- The first thread displays "Good Morning" every 1 second.
- The second thread displays "Hello" every 2 seconds.
- The third thread displays "Welcome" every 3 seconds.

Repeat the program using both methods.

## Software Requirements
- Java JDK
- Any Java IDE or terminal
- Git and GitHub

## Program 1: Extending Thread
**File name:** `ThreadExample.java`

Three classes extend the `Thread` class. The `run()` method displays the messages, and `Thread.sleep()` specifies the delay. The `start()` method starts each thread.

## Program 2: Implementing Runnable
**File name:** `RunnableExample.java`

Three classes implement the `Runnable` interface. Their objects are passed to the `Thread` constructor, and `start()` begins execution.

## Sample Output
```text
Good Morning
Hello
Welcome
Good Morning
Good Morning
Hello
Good Morning
Welcome
```

*Note: The output order may vary because the threads run concurrently.*

## How to Execute

### Program 1
```bash
javac ThreadExample.java
java ThreadExample
```

### Program 2
```bash
javac RunnableExample.java
java RunnableExample
```

Press `Ctrl+C` in the terminal to stop either program.

## Result
Successfully created and executed multiple Java threads using the `Thread` class and the `Runnable` interface.

## Author
Java Lab Student
