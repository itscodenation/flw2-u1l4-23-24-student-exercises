# Lesson 1.4: Arrays & Objects

## 📌 Key Concepts:

### 1. Arrays

- **Definition**: An array is a data structure in JavaScript used to store multiple values in a single variable.

    ```javascript
    let fruits = ["apple", "banana", "cherry"];
    ```

- **Index**: Each item in an array is assigned a number starting from 0, which is called its index.

    ```javascript
    fruits[0];  // "apple"
    ```

- **Length**: You can find out how many items are in an array with `.length`.

    ```javascript
    fruits.length;  // 3
    ```

- **Array Methods**: 
    - `.push()`: Add an element to the end.
    - `.pop()`: Remove the last element.
    - `.join()`: Combine all elements into a string.
    - `.splice()`: Add or remove elements from the array.

      ```javascript
      fruits.push("grape");  // Adds "grape" to the end
      fruits.pop();          // Removes the last item ("grape")
      ```

### 2. Objects

- **Definition**: Objects are collections of key-value pairs. They help associate different values together.

    ```javascript
    let book = {
      title: "Harry Potter",
      author: "J.K. Rowling",
      published: 1997
    };
    ```

- **Properties**: The keys in an object (like `title`, `author`, etc. in the above example) are called properties.

- **Accessing Values**: Use dot notation to access values in an object.

    ```javascript
    book.title;  // "Harry Potter"
    ```

- **Arrays in Objects**: Objects can hold arrays as values.

    ```javascript
    let student = {
      name: "Alice",
      subjects: ["Math", "Science", "English"]
    };
    student.subjects[1];  // "Science"
    ```

## 🧠 Remember:

1. Arrays are ordered lists, and you can access any element by its index.
2. Objects store data as key-value pairs and are great for representing entities with various attributes.
3. Always use the right data structure for your needs; sometimes, you might even use arrays and objects together!

## 💡 Tips:

- Always comment your code! It helps in understanding what each part of the code does.
  
    ```javascript
    // This is a single line comment in JavaScript
    ```

- If you're unsure about a method or property, search online or revisit this README.
  
Happy coding!