---
Title: '.clear()'
Description: 'Removes all elements from an ArrayList.' 
Subjects:
  - 'Java'
  - 'Data Structures'
Tags:
  - 'Method'
  - 'ArrayList'
  - 'Java'
CatalogContent:
  - 'learn-java'
  - 'paths/java-developer'
---

The **`.clear()`** method removes all elements from an [`ArrayList`](https://www.codecademy.com/resources/docs/java/array-list) in Java. 

## Syntax
All elements of an instance of `ArrayList` can be cleared by passing the `.clear()` method. After invoking this method, the list will be empty, but the `ArrayList` instance remains with its current capacity unchanged. It does not return anything but rather empties the list.

```pseudo
arrayListInstance.clear();
```

## Example
```java
import java.util.ArrayList;

public class Main {
    public static void main(String[] args) {
        // Create an ArrayList and add some elements
        ArrayList<String> fruits = new ArrayList<>();
        fruits.add("Apple");
        fruits.add("Banana");
        fruits.add("Cherry");
        
        System.out.println("Fruits: " + fruits);  // Output: Fruits: [Apple, Banana, Cherry]
        
        // Clear the ArrayList
        fruits.clear();
        
        System.out.println("Fruits after clear(): " + fruits);  // Output: Fruits after clear(): []
    }
}
```
## Codebyte Example

The example below shows the `.clear()` method being used to clear an `ArrayList` called `participant_ages`.

```codebyte/java
import java.util.ArrayList;

public class Main {
    public static void main(String[] args) {
        // Create an ArrayList and add ages
        ArrayList<String> participant_ages = new ArrayList<>();
        participant_ages.add("15");
        participant_ages.add("22");
        participant_ages.add("21");
        
        System.out.println("Ages of participants are: " + participant_ages);  // Output: Fruits: [15, 22, 21]
        
        // Clear the ArrayList
        participant_ages.clear();
        
        System.out.println("Ages of participants after clear(): " + participant_ages);  // Output: Ages of participants after clear: []
    }
}
```