# if-else:

The if statement alone tells us that if a condition is true it will execute a block of statements and if the condition is false it won’t. But what if we want to do something else if the condition is false? Here comes the else statement. We can use the else statement with the if statement to execute a block of code when the condition is false.

Syntax:
~~~java
if (condition)

{

    // Executes this block if

   // condition is true

}

else

{

// Executes this block if

// condition is false

}
~~~
**Control flow :**

![if else](https://github.com/rhushikesh2000/JAVA_TUTORIAL_/assets/124034778/39d23575-da45-47d6-9887-f2811b3a2223)


**Example:**
~~~java
int time = 20;
if (time < 18) {
  System.out.println("Good day.");
}
 else {
  System.out.println("Good evening.");
}
~~~
**Outputs:**
~~~java
Good evening.
~~~

