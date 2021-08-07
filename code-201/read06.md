# **JS Object Literals; The DOM**
![img](data:image/jpeg;base64,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)

## **Object Literals**

### **WHAT IS AN OBJECT?**
Objects group together a set of variables and functions to create a model of a something you would recognize from the real world. In an object, variables and functions take on new names. 

## **CREATING AN OBJECT:**
### **LITERAL NOTATION**

Literal notation is the easiest and most popular way to create objects. (There are several ways to create objects.)

The object is the curly braces and their contents. The objectis stored in avariable cated hotel,
so you would refer to it as the hotel object.

Separate each key from its value using acolon. Separate each property and method witha comma, but net after the last value.


## **ACCESSING AN OBJECT AND DOT NOTATION**

You access the properties or methods of an object using dot notation. You can also access properties using square brackets.

To access a property or method of an object you use the name of the object, followed by a period then, the name of the property or method you want to access. This is known as dot notation

The period is known as the memher operatar. The property or method on its right is a member of the
object on its left. 

___


## **The Document Object Model** 

![img](https://previews.123rf.com/images/timbrk/timbrk1603/timbrk160300391/54593957-document-object-model-web-development-acronym-dom-of-the-yellow-square-pixels-on-a-black-matrix-back.jpg)

(DOM) specifies how browsers should create a model of an HTML page and how JavaScript can access and update the contents of a web page while it is  in the browser window.

###### The DOM is neither part of HTML, nor part of JavaScript; it is a separate set of rules. It is implemented by all major browser makers, and covers two primary areas: 

* ###  **MAKING A MODEL OF THE HTML PAGE**

When the browser loads a web page, it creates a model of the page in memory.

The ***DOM*** specifies the way in which the browser should structure this model using a ***DOM*** tree.

The ***DOM*** is called an object model because the model (the ***DOM*** tree) is made of objects.

Each object represents a different part of the page loaded in the browser window.

* ### **ACCESSING AND CHANGING THE HTML PAGE**

The DOM also defines methods and properties to access and update each object in this model, which in turn updates what the user sees in the browser. 

## **THE DOM TREE IS A MODEL OF A WEB PAGE**

As a browser loads a web page, it creates a model of t hat page. The model is called a DOM t ree, and it is stored in the browsers' memory. It consists of four main types of nodes. 

BODY OF HTML PAGE 

<**html**>

  <**body**>

   <**div**  id="page">

    <hl id="header">List</hl> <h2>Buy groceries</h2> 
    <ul>
     <li id="one" class="hot"><em>fresh</em> figs</li> 
     <li id="two" class="hot">pine nuts</li> 
     <li  id="three" class="hot">honey</li > 
     <li  id="four">balsamic vinegar</li> 
    </ul> 

   <**script** src="js/l i st.js"></**script**> 

  </**div**>

 </**body**>

</**html**>


* ### **THE DOCUMENT NODE**

Above, you can see the HTML code for a shopping list, and on the right hand page is its DOM tree. Every element, attribute, and piece of text in the HTML is represented by its own DOM n ode. At the top of the tree a document node is added; it represents the entire page (and also corresponds to the document object, which you first met on p36).

When you access any element, attribute, or text node, you navigate to it via the document node. It is the starting point for al l visits to the DOM tree.


* ### **ELEMENT NODES**

HTML elements describe the structure of an HTML page. (The <**hl** > - <**h6**> elements describe what parts are headings; the <**p**> tags indicate where paragraphs of text start and finish; and so on.) 

To access the DOM tree, you start by looking for elements. Once you find the element you want, then you can access its text and attribute nodes if you want to. This is why you start by learning methods that allow you to access element nodes, before learning to access and alter text or attributes. 
