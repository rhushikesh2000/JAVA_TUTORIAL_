

# Multithreading in Java

Multithreading is a Java feature that allows concurrent execution of two or more parts of a program for maximum utilization of CPU. Each part of such program is called a thread. So, threads are light-weight processes within a process.


![multithreading](https://github.com/rhushikesh2000/JAVA_TUTORIAL_/assets/124034778/5239c30f-2561-423a-9afb-327a36ea5e40)


**Advantages of Java Multithreading**

---

1.It doesn't block the user because threads are independent and you can perform multiple operations at the same time.

2.You can perform many operations together, so it saves time.

3.Threads are independent, so it doesn't affect other threads if an exception occurs in a single thread.

**Multitasking**

---
Multitasking is a process of executing multiple tasks simultaneously. We use multitasking to utilize the CPU. Multitasking can be achieved in two ways:

- Process-based Multitasking (Multiprocessing)
- Thread-based Multitasking (Multithreading)

**1. Process-based Multitasking (Multiprocessing)**

---

- Each process has an address in memory. In other words, each process allocates a separate memory area.
- A process is heavyweight.
- Cost of communication between the process is high.
- Switching from one process to another requires some time for saving and loading registers, memory maps, updating lists, etc.

**2. Thread-based Multitasking (Multithreading)**

- Threads share the same address space.
- A thread is lightweight.
- Cost of communication between the thread is low.
   
