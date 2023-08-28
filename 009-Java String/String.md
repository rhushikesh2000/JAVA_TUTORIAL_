# String 




**What are Strings in Java?**

---

Strings are the type of objects that can store the character of values. A string acts the same as an array of characters in Java.

Example:  
~~~java

String name = "Geeks";
~~~
![Aspose Words 80554fad-41a6-47b8-8ff7-40351f20e020 001](https://github.com/rhushikesh2000/Java_tutorial/assets/124034778/d9cf0624-f97b-43bc-a25a-dec5c252e19a)







**Ways of Creating a String**

---

**There are two ways to create a string in Java:**

- String Literal
- Using new Keyword


**1. String literal**

---

To make Java more memory efficient (because no new objects are created if it exists already in the string constant pool). 


Example:
~~~java
String demoString = “WelCome to Guvi”;
~~~

**2. Using new keyword**

---
~~~java
String s = new String(“Welcome”);
~~~
In such a case, JVM will create a new string object in normal (non-pool) heap memory and the literal “Welcome” will be placed in the string constant pool. The variable s will refer to the object in the heap (non-pool)



**Java.lang.String class in Java**

---

Strings in java are immutable. Now lets discuss some of the methods provided by String class. Methods:






|**Methods**          |**Description**|
| :- | :- |
|contains()|checks whether the string contains a substring|
|substring()|returns the substring of the string|
|join()|join the given strings using the delimiter|
|replace()|replaces the specified old character with the specified new character|
|replaceAll()|replaces all substrings matching the regex pattern|
|replaceFirst()|replace the first matching substring|
|charAt()|returns the character present in the specified location|
|getBytes()|converts the string to an array of bytes|
|indexOf()|returns the position of the specified character in the string|
|compareTo()|compares two strings in the dictionary order|
|compareToIgnoreCase()|compares two strings ignoring case differences|
|trim()|removes any leading and trailing whitespaces|
|format()|returns a formatted string|
|split()|breaks the string into an array of strings|
|toLowerCase()|converts the string to lowercase|
|toUpperCase()|converts the string to uppercase|
|valueOf()|returns the string representation of the specified argument|
|toCharArray()|converts the string to a char array|
|matches()|checks whether the string matches the given regex|
|startsWith()|checks if the string begins with the given string|
|endsWith()|checks if the string ends with the given string|
|isEmpty()|checks whether a string is empty of not|
|intern() |returns the canonical representation of the string|
|contentEquals()|checks whether the string is equal to charSequence|
|hashCode()|returns a hash code for the string|
|subSequence()|returns a subsequence from the string|

**Why Java Strings are immutable in nature?**

---

The String pool cannot be possible if String is not immutable in Java. A lot of heap space is saved by JRE. The same string variable can be referred to by more than one string variable in the pool. String interning can also not be possible if the String would not be immutable.

If we don’t make the String immutable, it will pose a serious security threat to the application. For example, database usernames, and passwords are passed as strings to receive database connections. The socket programming host and port descriptions are also passed as strings. The String is immutable, so its value cannot be changed. If the String doesn’t remain immutable, any hacker can cause a security issue in the application by changing the reference value.

