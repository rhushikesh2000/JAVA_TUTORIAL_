

# Do-While loop :

Java do-while loop is an Exit control loop. Therefore, unlike for or while loop, a do-while check for the condition after executing the statements of the loop body.

**Syntax**
~~~java
do

{

    // Loop Body

    Update\_expression

}

// Condition check

while (test\_expression);
~~~

**Execution of do-While loop** 

1. Control falls into the do-while loop.
1. The statements inside the body of the loop get executed.
1. Updation takes place.
1. The flow jumps to Condition
1. Condition is tested. 
1. If Condition yields true, go to Step 6.
1. If Condition yields false, the flow goes outside the loop
1. The flow goes back to Step 2.

**Control Flow**

![do while](https://github.com/rhushikesh2000/JAVA_TUTORIAL_/assets/124034778/1539b253-c825-4ac2-960d-38ade19623d0)


**Example**

~~~java
class Guvi {
 
    // Main driver method
    public static void main(String[] args)
    {
        // initial counter variable
        int i = 0;
 
        do {
 
            // Body of loop that will execute minimum
            // 1 time for sure no matter what
            System.out.println("Print statement");
            i++;
        }
 
        // Checking condition
        // Note: It is being checked after
        // minimum 1 iteration
        while (i < 0);
    }
}
~~~

**Output**
~~~
Print statement
~~~

