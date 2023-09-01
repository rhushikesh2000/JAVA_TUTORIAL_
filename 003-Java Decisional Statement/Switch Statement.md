


# Switch Statement :

It is like an if-else-if ladder statement. It provides an easy way to dispatch execution to different parts of code based on the value of the expression. The expression can be a byte, short, char, or int primitive data type. It tests the equality of variables against multiple values.

**Some Important Rules for Switch Statements**

- There can be any number of cases just imposing condition check but remember duplicate case/s values are notallowed.
- The value for a case must be of the same data type as the variable in the switch.
- The value for a case must be constant or literal. Variables are not allowed.
- The break statement is used inside the switch to terminate a statement sequence.
- The break statement is optional. If omitted, execution will continue into the next case.
  
Syntax :

~~~java
// switch statement 

switch(expression)

{
   // case statements

   // values must be of the same type of expression

case value1 :

     // Statements

      break; // break is optional



case value2 :

      // Statements

      break; // break is optional



   // We can have any number of case statements

   // below is the default statement, used when none of the cases is true. 

  // No break is needed in the default case.

   default :

     // Statements }

~~~

**Control Flow**

![switch](https://github.com/rhushikesh2000/JAVA_TUTORIAL_/assets/124034778/658efce6-1f59-4c4c-bd49-26e33845f054)

**Example:**

~~~java
class GFG {
    public static void main (String[] args) {
        int num=20;
          switch(num){
          case 5 :  System.out.println("It is 5");
                    break;
          case 10 : System.out.println("It is 10");
                    break;
          case 15 : System.out.println("It is 15");
                    break;
          case 20 : System.out.println("It is 20");
                    break;
          default:  System.out.println("Not present");
             
        }
    }
}
~~~

**Output:**
~~~java
It is 20
~~~

