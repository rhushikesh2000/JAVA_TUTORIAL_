**JAVA Terminology**
---

![java term](https://github.com/rhushikesh2000/JAVA_TUTORIAL_/assets/124034778/868b4a30-043d-4d5d-a8c7-6fd4d1552e5b)


**Java Development Kit (JDK)**
---

As the name formally states, Java Development Kit is a full-time kit that has a compiler, Java Runtime Environment(JRE), Debuggers, and Java documents included in it. For further execution in Java, we need to have JDK installed on our computers to further lead to the creation, compilation, and running of the Java program.

Here, as we use JDK, we need an environment to run the programs. We use JRE Java Runtime Environment, which provides the least requirements to execute the Java program. It provides the JVM, Core classes, and supporting files.


![jdk](https://github.com/rhushikesh2000/JAVA_TUTORIAL_/assets/124034778/ffa7b7b7-b5df-4581-92fe-59bb02e2a890)


**Java Run-time Environment (JRE)**
---

JDK includes JRE, which, in turn, after installation, allows the Java program to run. But we still can't compile it. It has a browser, the applet supports, and a few plugins included in it. So, to run a java program on your respective computers, you need JRE.

**JRE is made up of multiple elements altogether, and they are:**

1. Java virtual machine (JVM)
2. Java class libraries
3. Java class loader

**Java Virtual Machine (JVM)**
---

It is a very important part not only of JDK but also JRE as it is inbuilt in both of the places. When you run a program using the JRE and JDK, it also goes to the JVM as it is required to run the java program and interprets the program. 

**Run the Code**: JVM runs the bytecode provided by the compiler. Since Java is a platform-independent language, the compiled code produced by the JAVAC compiler is converted to machine code using platform specific JVMs. Different platforms have different JVMs. JVMs convert the bytecode into platform specific machine code.


**Bytecode in the Development Process**
---

The source code provided to the JAVAC compiler that is present in JDK gets compiled into a bytecode that the JVM can execute. It gets saved as a .class file by the compiler itself. We can also view this bytecode using a disassembler like javap.

![byte process](https://github.com/rhushikesh2000/JAVA_TUTORIAL_/assets/124034778/15b60556-33e8-4a7a-9421-2be68876a4cd)







