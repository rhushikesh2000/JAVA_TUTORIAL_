

# nested-if:

A nested if is an if statement that is the target of another if or else. Nested if statements mean an if statement inside an if statement. Yes, java allows us to nest if statements within if statements. i.e., we can place an if statement inside another if statement.

**Syntax:**
~~~java
if (condition1)

{

   // Executes when condition1 is true

   if (condition2) 

  {

      // Executes when condition2 is true

}

}
~~~
**Control Flow**

![nested if](https://github.com/rhushikesh2000/JAVA_TUTORIAL_/assets/124034778/949a8b70-c1e7-437d-9963-d16d20c48f87)



**Example**
~~~java
class guvi
{  
    public static void main(String args[])
    {
        int a=10;
          int b=20;
       
        if(a==10){
            if(b==20){
                System.out.println("welcome");
            }
        }
    }
}

~~~
**Output:**
~~~java
Welcome
~~~
