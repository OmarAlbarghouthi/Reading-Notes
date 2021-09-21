# **Functional Programming Concepts**

### **Q1. What is functional programming?** 

Functional programming is a programming paradigm — a style of building the structure and elements of computer programs — that treats *computation* as the *evaluation* of mathematical functions and avoids changing-state and mutable data.

### **Q2. What is a pure function and how do we know if something is a pure function?**

A pure function is one of the fundamental concepts of functional programming, and we can know if the function is pure when:

- It returns the same result if given the same arguments.
- It does not cause any observable side effects.

### **Q3. What are the benefits of a pure function?**

- Testable.
- No need for mocking anything.
- Easier maintaining, refactoring, and testing.


### **Q4. What is immutability?**

***Immutability*** means that it can't be changed (unchangeable)

### **Q5. What is Referential transparency?**

Referential transparency and referential opacity are properties of parts of computer programs. An expression is called referentially transparent if it can be *replaced* with its corresponding value (and vice-versa) without changing the program's behavior. (**pure** *+* **immutability** *=* **referential transparency**)

_______
_______

# **Node JS: Modules and require()**

### **Q1. What is a module?**

**Modules** in **Node.js** are a set of functionalities that can be called whenever are needed.

### **Q2. What does the word ‘require’ do?** 

It imports the data from a module, given it's path.

### **Q3. How do we bring another module into the file the we are working in?**

We can do that by using the word require and give it the *path* of the module.

### **Q4. What do we have to do to make a module available? **

We can do that by using module.exports = what ever we want to make available.

Like that we can export the data which we want to make available.