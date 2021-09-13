# **React Docs - lists and keys**

### **Q1. What does .map() return?**

map() function returns a map object(which is an iterator) of the results after applying the given function to each item of a given iterable (list, tuple etc.) ... fun : It is a function to which map passes each element of given iterable. iter : It is a iterable which is to be mapped.

### **Q2. If I want to loop through an array and display each value in JSX, how do I do that in React?**

> const numbers = [1, 2, 3, 4];
const listItems = numbers.map((number) =>
  <**li**>{number}</**li**>
);
ReactDOM.render(
  <**ul**>{listItems}</**ul**>,
  document.getElementById('root')
);

### **Q3. Each list item needs a unique ____.**

## **Key**

### **Q4. What is the purpose of the key?**

 Keys are used to React to identify which items in the list are changed, updated, or deleted.



 # **Spreed Operator**

 ### **Q1. What is Spread operator?**

 The spread operator is a new addition to the set of operators in JavaScript ES6. It takes in an iterable (e.g an array) and expands it into individual elements. The spread operator is commonly used to make shallow copies of JS objects. Using this operator makes the code concise and enhances its readability.

 ### **List 4 things that the spread operator can do.**

 * Using an array as arguments

* Adding an item to a list

* Adding to state in React

* Combining objects

### **Q3. Give an example of using the spread operator to combine two arrays.**

> const array1 = ['a',`ab`,`abc`]
const array2 = [`d`,`de`,`def`]
const arrayconcat = [...array1,...array2]
console.log(...arrayconcat) 

### **Q4. Give an example of using the spread operator to add a new item to an array.**

> const names = ['Omar', 'ahmad', 'Angela'];
const moreNames = ['John', ...names];
console.log(moreNames);


### **Q5.Give an example of using the spread operator to combine two objects into one.**

> const objectOne = {p1: 'Hello Im object 1'};
const objectTwo = {p2: 'Hellow Im object 2'};
const objectThree = {...objectOne, ...objectTwo, p3: 'Hellow Im object 3'};
console.log(objectThree);
const objectFour = {...objectOne, ...objectTwo, p4: () => {console.log("Hellow Im object 4".repeat(5))}};
objectFour.p4();

# **How to Pass Functions Between Components**

### **Q1.**

In the video the map() function used to loop over the array of objects.

### **Q2.**

This function loops over the array of objects to find the passed name to be able to update/increment the count.

### **Q3.**

In order to pass a method from a parent to a child you basically need to use props.

### **Q4.**

The child can invoke a method that was passed to it from the parent by making a prop out of it and then using the prop to access the method and invoke it. ex: this.props.methodName();