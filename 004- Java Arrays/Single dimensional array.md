
**What is Array**

---

Normally, an array is a collection of similar type of elements which has a contiguous memory location.

Java array is an object which contains elements of a similar data type. Additionally, The elements of an array are stored in a contiguous memory location. It is a data structure where we store similar elements. We can store only a fixed set of elements in a Java array. Array in Java is index-based, the first element of the array is stored at the 0th index, 2nd element is stored on 1st index, and so on.

![Aspose Words fa48cee7-5a27-44b0-b207-89444d2a6cf3 001](https://github.com/rhushikesh2000/JAVA_TUTORIAL_/assets/124034778/b9f0f36c-3626-45e8-b576-6cde980d956d)






**Why we need array?**

---

Arrays in Java are essential data structures that allow us to store and manage multiple elements of the same data type in a single variable. They provide efficient memory allocation and fast access to elements, making it easier to work with collections of data and perform various operations like sorting, searching, and iteration.


**Creating, initializing, and accessing an Array**

The general form of a one-dimensional array declaration is

**Syntax:**
~~~java
Datatype var-name[];

OR

Datatype [] var-name;


~~~

**Instantiating an Array in Java**

When an array is declared, only a reference of an array is created. To create or give memory to the array, you create an array like this: The general form of new as it applies to one-dimensional arrays appears as follows: 

**Syntax:**
~~~java
var-name = new type [size];
~~~

**Example:**
~~~java

int intArray[];    //declaring array

intArray = new int[20];  // allocating memory to array
~~~


**Array Literal**

---

In a situation where the size of the array and variables of the array are already known, array literals can be used. 
~~~java
int[] intArray = { 1,2,3,4,5,6,7,8,9,10 }; 

// Declaring array literal
~~~
- The length of this array determines the length of the created array.
- There is no need to write the new int[] part in the latest versions of Java.

- Accessing Java Array Elements using for Loop

Each element in the array is accessed via its index. The index begins with 0 and ends at (total array size)-1. 

All the elements of array can be accessed using Java for Loop.
~~~java
// accessing the elements of the specified array

for (int i = 0; i < arr.length; i++){
System. out.println("Element at index " +i+" "+arr[i]);
}
~~~

**Arrays of Objects**

---

An array of objects is created like an array of primitive-type data items in the following way. 
~~~java
Student[] arr = new Student[5]; //student is a user-defined class
~~~
**Syntax:**
~~~java

1. data type[] arrName;

2. datatype arrName[];

3. datatype [] arrName;

~~~

**What happens if we try to access elements outside the array size?**

---

JVM throws ArrayIndexOutOfBoundsException to indicate that the array has been accessed with an illegal index. The index is either negative or greater than or equal to the size of an array.