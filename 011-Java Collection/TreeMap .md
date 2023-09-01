## TreeMap 


Java TreeMap class is a red-black tree based implementation. It provides an efficient means of storing key-value pairs in sorted order.

![treemap](https://github.com/rhushikesh2000/JAVA_TUTORIAL_/assets/124034778/7b101565-e49b-4ced-ae81-c563803bad6d)


**The important points about Java TreeMap class are:**

---

- Java TreeMap contains values based on the key. It implements the NavigableMap interface and extends AbstractMap class.
- Java TreeMap contains only unique elements.
- Java TreeMap cannot have a null key but can have multiple null values.
- Java TreeMap is non synchronized.
- Java TreeMap maintains ascending order.

**Constructors:**

---

|**Constructor**|**Description**
| :-: | :-: |
|TreeMap()|It is used to construct an empty tree map that will be sorted using the natural order of its key.|
|TreeMap(Comparator<? super K> comparator)|It is used to construct an empty tree-based map that will be sorted using the comparator comp.|
|TreeMap(Map<? extends K,? extends V> m)|It is used to initialize a treemap with the entries from **m**, which will be sorted using the natural order of the keys.|
|TreeMap(SortedMap<K,? extends V> m)|It is used to initialize a treemap with the entries from the SortedMap **sm**, which will be sorted in the same order as **sm.**|



**Java TreeMap Example**

```java
import java.util.*;  
class TreeMap1{  
 public static void main(String args[]){  
   TreeMap<Integer,String> map=new TreeMap<Integer,String>();    
      map.put(100,"Amit");    
      map.put(102,"Ravi");    
      map.put(101,"Vijay");    
      map.put(103,"Rahul");    
        
      for(Map.Entry m:map.entrySet()){    
       System.out.println(m.getKey()+" "+m.getValue());    
      }    
 }  
}  
```
Output
```
       100 Amit
       101 Vijay
       102 Ravi
       103 Rahul
```

---------

```java
import java.util.*;  
class TreeMap3{  
 public static void main(String args[]){  
   NavigableMap<Integer,String> map=new TreeMap<Integer,String>();    
      map.put(100,"Amit");    
      map.put(102,"Ravi");    
      map.put(101,"Vijay");    
      map.put(103,"Rahul");    
      //Maintains descending order  
      System.out.println("descendingMap: "+map.descendingMap());  
      //Returns key-value pairs whose keys are less than or equal to the specified key.  
      System.out.println("headMap: "+map.headMap(102,true));  
      //Returns key-value pairs whose keys are greater than or equal to the specified key.  
      System.out.println("tailMap: "+map.tailMap(102,true));  
      //Returns key-value pairs exists in between the specified key.  
      System.out.println("subMap: "+map.subMap(100, false, 102, true));   
 }  
} 
```

Output
```
descendingMap: {103=Rahul, 102=Ravi, 101=Vijay, 100=Amit}
headMap: {100=Amit, 101=Vijay, 102=Ravi}
tailMap: {102=Ravi, 103=Rahul}
subMap: {101=Vijay, 102=Ravi}
```
