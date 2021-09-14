# **React and Forms**

### **Q1. What is a Controlled Components?**

An input form element whose value is controlled by React in this way is called a “controlled component”.

### **Q2. Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.**

Yes, we should wait, because there is a possibility that the user will change his mind about one of the responses, so it is better to wait until the user sends the responses.

### **Q3How do we target what the user is entering if we have an event handler on an input field?.**

We can target the user's input by using the input field.

____

# **The Conditional (Ternary) Operator**


### **Q1. Why would we use ternary operator?**

A ternary operator allows you to assign one value to the variable if the condition is true, and another value if the condition is false.

A ternary operator makes the assignment of a value to a variable easier to see, because it's contained on a single line instead of an if else block.

### **Q2. Rewrite the following statement using a ternary statement:**


**ex:**

 if (x===y) {

 console.log(true);

  } else {

 console.log(false);
  }


**ternary statement:**

>console.log(x===y ? 'true' : 'false');