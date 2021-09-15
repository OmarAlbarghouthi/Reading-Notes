# ***Putting it all together***

* ##  **Thinking in React**

### **Q1. What is the *single responsibility principle* and how does it apply to components?**

In short, the Single Responsibility Principle means that code with the same functionality should not exist in multiple places.


### **Q2. What does it mean to build a ‘static’ version of your application?**

Static applications are just that, static. **They don't move**. You can basically put them on a Smartphone or tablet and they will fully work without any internet or data connection.

### **Q3. Once you have a static application, what do you need to add?**

Once I have a static application I need to start adding interactivity, but first I need to identify the minimal set of mutable state that the app needs.

### **Q4. What are the three questions you can ask to determine if something is state?**

>Is it passed in from a parent via props? If so, it probably isn’t state.

>Does it remain unchanged over time? If so, it probably isn’t state.

>Can you compute it based on any other state or props in your component? If so, it isn’t state.


### **Q5. How can you identify where state needs to live?**

* Identify every component that renders something based on that state.

* Find a common owner component (a single component above all the components that need the state in the hierarchy).

* Either the common owner or another component higher up in the hierarchy should own the state.

* If you can’t find a component where it makes sense to own the state, create a new component solely for holding the state and add it somewhere in the hierarchy above the common owner component.

_____

* ## **Higher-Order Functions**

### **Q1. What is a “higher-order function”?**


Higher-order functions are functions that take other functions as arguments or return functions as their results. Sort, reduce, filter, forEach are other examples of higher-order functions built into the language.

### **Q2. Explore the greaterThan function as defined in the reading. In your own words, what is line 2 of this function doing?**

In line 2 the function is returning an arrow function that compares the arrow function passed variable ‘m to the main function passed variable ‘n’.

### **Q3. Explain how either map or reduce operates, with regards to higher-order functions.**


Reduce function takes 3 parameters, an array, a function, and a starting point, in this example the array is [1, 2, 3, 4] and the function works on taking the starting point and each element from the array and combine them together, then returns it to the starting point again to change it. All of this means that this reduce function takes an array and a starting point and makes some operations on them using the passed function.

____