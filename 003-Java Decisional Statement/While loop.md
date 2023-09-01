
# While loop :

A while loop is a control flow statement that allows code to be executed repeatedly based on a given Boolean condition. The while loop can be thought of as a repeating if statement.

**Syntax**

~~~java
while (test\_expression)

{

   // statements



 update\_expression;

}
~~~

**Control flow**

![while](https://github.com/rhushikesh2000/JAVA_TUTORIAL_/assets/124034778/59ca5f98-4a76-4ee9-a329-4bfaca72ea06)

                
**Example**

~~~java
class whileLoopDemo {
    public static void main(String args[])
    {
        // initialization expression
        int i = 1;
 
        // test expression
        while (i < 6) {
            System.out.println("Hello World");
 
            // update expression
            i++;
        }
    }
}
~~~

**Output**
~~~
Hello World
Hello World
Hello World
Hello World
Hello World
~~~

**How Does a While loop execute?** 

1. Control falls into the while loop.
1. The flow jumps to Condition
1. Condition is tested. 
1. If the Condition yields true, the flow goes into the Body.
1. If the Condition yields false, the flow goes outside the loop
1. The statements inside the body of the loop get executed.
1. Updation takes place.
1. Control flows back to Step 2.
1. The while loop has ended and the flow has gone outside.
