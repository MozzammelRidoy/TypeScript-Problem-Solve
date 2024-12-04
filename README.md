# Basic Problem Solving with TypeScript

This repository contains solutions to fundamental TypeScript problems. Each problem demonstrates key TypeScript concepts like data typing, interfaces, classes, type checking, and data structure manipulation.

---

## 📝 Problem List

1. **Sum of Array**  
   Write a TypeScript function `sumArray` that takes an array of numbers and returns the sum of all elements in the array.  
   **Example:** `sumArray([1, 2, 3, 4, 5]); // 15`

2. **Remove Duplicates**  
   Create a TypeScript function `removeDuplicates` that accepts an array of numbers and returns a new array with duplicates removed, preserving the original order of elements.  
   **Example:** `removeDuplicates([1, 2, 2, 3, 4, 4, 5]); // [1, 2, 3, 4, 5]`

3. **Word Occurrence Counter**  
   Create a TypeScript function `countWordOccurrences` that accepts a sentence (string) and a word (string). The function should return the number of times the word appears in the sentence, ignoring case.  
   **Example:** `countWordOccurrences("I love typescript", "typescript"); // 1`

4. **Calculate Shape Area**  
   Define a union type `Circle` and `Rectangle`, where each type has a unique `shape` property. Create a function `calculateShapeArea` that uses type guards to calculate the area based on the shape type.  
   **Example 1:** `calculateShapeArea({ shape: "circle", radius: 5 }); // 78.54`  
   **Example 2:** `calculateShapeArea({ shape: "rectangle", width: 4, height: 6 }); // 24`

5. **Generic Property Getter**  
   Write a generic function `getProperty` that takes an object and a property name as arguments and returns the property value. Add a constraint to ensure the property name exists on the object.  
   **Example:** `const person = { name: "Alice", age: 30 }; getProperty(person, "name"); // "Alice"`

6. **Profile Updater**  
   Define an interface `Profile` with properties `name`, `age`, and `email`. Create a function `updateProfile` that accepts an object of type `Profile` and an object of type `Partial<Profile>` representing the updates. The function should return the updated profile.  
   **Example:** `const myProfile = { name: "Alice", age: 25, email: "alice@example.com" }; updateProfile(myProfile, { age: 26 }); // { name: "Alice", age: 26, email: "alice@example.com" }`

7. **Car Class**  
   Create a TypeScript class `Car` with properties `make`, `model`, and `year`. Include a method `getCarAge` that returns the car's age based on the current year.  
   **Example:** `const car = new Car("Honda", "Civic", 2018); car.getCarAge(); // 6`
