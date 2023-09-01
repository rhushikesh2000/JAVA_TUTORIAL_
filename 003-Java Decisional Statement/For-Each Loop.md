

# For-Each Loop

Enhanced For Loop or Java For-Each loop in Java is another version of for loop introduced in Java 5. Enhanced for loop provides a simpler way to iterate through the elements of a collection or array. It is inflexible and should be used only when there is a need to iterate through the elements in a sequential manner without knowing the index of the currently processed element.

**Syntax**

~~~java
for (T element: Collection obj/array)

{

    // loop body

   // statement(s)

}
~~~

**Control Flow**

![for each](https://github.com/rhushikesh2000/JAVA_TUTORIAL_/assets/124034778/e6f7aef7-f575-4834-b526-5a5bd811bc68)


**Example**

~~~java
class Easy
  
{
  
    public static void main(String[] args)
  
    {
  
        // array declaration
  
        int ar[] = { 10, 50, 60, 80, 90 };
  
        for (int element : ar)
  
            System.out.print(element + " ");
    }
}
~~~

**Output**
~~~
10 50 60 80 90 
~~~
