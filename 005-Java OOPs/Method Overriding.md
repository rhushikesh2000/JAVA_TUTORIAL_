# Method Overriding in Java



If subclass (child class) has the same method as declared in the parent class, it is known as method overriding in Java.

In other words, If a subclass provides the specific implementation of the method that has been declared by one of its parent class, it is known as method overriding.

**Usage of Java Method Overriding**

---

   - Method overriding is used to provide the specific implementation of a method which is already provided by its superclass.
   - Method overriding is used for runtime polymorphism

**Rules for Java Method Overriding**

---


   1. The method must have the same name as in the parent class
   2. The method must have the same parameter as in the parent class.
   3. There must be an IS-A relationship (inheritance).
   


![rule overriding](https://github.com/rhushikesh2000/JAVA_TUTORIAL_/assets/124034778/d95645d8-574d-4e25-802b-596afad57adc)



**Example:**

```java

//Creating a parent class  

 class Vehicle{  
   //defining a method  
   void run(){

System.out.println("Vehicle is running");
}  
 }  
 //Creating a child class  
 class Bike2 extends Vehicle{
 
   //defining the same method as in the parent class  
   void run(){

System.out.println("Bike is running safely");
}  
   
   public static void main(String args[]){

   Bike2 obj = new Bike2();//creating object  
   obj.run();//calling method  
   }  
 }  
```
Output:
~~~
Bike is running safely
~~~

In this example, we have defined the run method in the subclass as defined in the parent class but it has some specific implementation. The name and parameter of the method are the same, and there is IS-A relationship between the classes, so there is method overriding. 


**A real example of Java Method Overriding**

---

Consider a scenario where Bank is a class that provides functionality to get the rate of interest. However, the rate of interest varies according to banks. For example, SBI, ICICI and AXIS banks could provide 8%, 7%, and 9% rate of interest.

![real exaple overriding](https://github.com/rhushikesh2000/JAVA_TUTORIAL_/assets/124034778/90c599fe-a2fc-4f9c-9e34-d8a0e8ac9f60)



Example
```java
class Bank{  
int getRateOfInterest(){
return 0;
}  
}  
//Creating child classes.  
class SBI extends Bank{

int getRateOfInterest(){
return 8;
}  
}  
  
class ICICI extends Bank{  
int getRateOfInterest()
{
return 7;
}  
}  
class AXIS extends Bank{  
int getRateOfInterest(){
return 9;
}  
}

//Test class to create objects and call the methods  
class Test2{

public static void main(String args[]){  
SBI s=new SBI();  
ICICI i=new ICICI();  
AXIS a=new AXIS();

System.out.println("SBI Rate of Interest: "+s.getRateOfInterest());  
System.out.println("ICICI Rate of Interest: "+i.getRateOfInterest());  
System.out.println("AXIS Rate of Interest: "+a.getRateOfInterest());  
}  
} 
```
Output:
~~~
8
7
9
~~~


**Can we override static method?**

---
No, a static method cannot be overridden. It can be proved by runtime polymorphism, so we will learn it later.

**Why can we not override static method?**

---
It is because the static method is bound with class whereas instance method is bound with an object. Static belongs to the class area, and an instance belongs to the heap area. 
