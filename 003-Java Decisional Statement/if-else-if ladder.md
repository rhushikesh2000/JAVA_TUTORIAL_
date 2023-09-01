

# if-else-if ladder: 

Here, a user can decide among multiple options. The if statements are executed from the top down. As soon as one of the conditions controlling the if is true, the statement associated with that ‘if’ is executed, and the rest of the ladder is bypassed. If none of the conditions is true, then the final else statement will be executed. There can be as many as ‘else if’ blocks associated with one ‘if’ block but only one ‘else’ block is allowed with one ‘if’ block.

Syntax:
~~~java
if(Boolean_expression 1) {
   // Executes when the Boolean expression 1 is true
}
else if(Boolean_expression 2) {

   // Executes when the Boolean expression 2 is true
}
else if(Boolean_expression 3) {

   // Executes when the Boolean expression 3 is true
}
else {

   // Executes when the none of the above condition is true.
}
~~~
**control Flow**

![if else if](https://github.com/rhushikesh2000/JAVA_TUTORIAL_/assets/124034778/94eaffdf-2716-411e-b5ca-2866804d2c58)



**Example:**
~~~java
class ifelseifDemo {
    public static void main(String args[])
    {
        int i = 20;
 
        if (i == 10)
            System.out.println("i is 10");
        else if (i == 15)
            System.out.println("i is 15");
        else if (i == 20)
            System.out.println("i is 20");
        else
            System.out.println("i is not present");
    }
}
~~~
**Output:**
~~~java
i is 20
~~~
