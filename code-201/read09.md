# **HTML Forms and JS Events**

## **HTML Form**

### **What HTML form means?**


An HTML form is a section of a document containing normal content, markup, special elements called controls (checkboxes, radio buttons, menus, etc.), and labels on those controls.

### **What are HTML controls?**
Image result
The HTML controls such as the header tags, anchor tags, and input elements are not processed by the server but are sent to the browser for display. They are specifically converted to a server control by adding the attribute runat="server" and adding an id attribute to make them available for server-side processing.


### **Can we create a form in HTML?**
The elements used in an HTML form are check box, input box, radio buttons, submit buttons etc. Using these elements the information of an user is submitted on a web server. The form tag is used to create an HTML form.

### **What is required in HTML form?**

The required attribute is a boolean attribute. When present, it specifies that an input field must be filled out before submitting the form. Note: The required attribute works with the following input types: text, search, url, tel, email, password, date pickers, number, checkbox, radio, and file.

### **What does HTML form submit do?**

The <**input type="submit">** <input type="submit">defines a submit button which submits all form values to a form-handler. The form-handler is typically a server page with a script for processing the input data. The form-handler is specified in the form's action attribute.

_____
## **JavaScript Events**

The change in the state of an object is known as an **Event**. In html, there are various events which represents that some activity is performed by the user or by the browser. When javascript code is included in HTML, js react over these events and allow the execution. This process of reacting over the events is called **Event Handling**. Thus, js handles the HTML events via **Event Handlers**.

**For example**, when a user clicks over the browser, add js code, which will execute the task to be performed on the event.

**Some of the HTML events and their event handlers are:**

* ## **Mouse events:**

Event Performed	| Event Handler	| Description
----------|---------|-----------
click     |onclick  |When mouse click on an element
mouseover |onmouseover|When the cursor of the mouse comes over the element
mouseout  |onmouseout|When the cursor of the mouse leaves an element
mousedown |onmousedown|When the mouse button is pressed over the element
mouseup   |onmouseup|When the mouse button is released over the element
mousemove |onmousemove|When the mouse movement takes place.
________
* ## **Keyboard events:**

Event Performed|Event Handler | Description
---------------|----------------|--------------
Keydown & Keyup| onkeydown & onkeyup|	When the user press and then release the key
_________
* ## **Form events:**


Event Performed | Event Handler | Description
----------|---------|----------
focus|onfocus|	When the user focuses on an element
submit|	onsubmit|	When the user submits the form
blur|	onblur|	When the focus is away from a form element
change|	onchange|	When the user modifies or changes the value of a form element
_________
* ## **Window/Document events:**
Event Performed|	Event Handler|	Description
--------|---------|------------
load|	onload|	When the browser finishes the loading of the page
unload|	onunload|	When the visitor leaves the current webpage, the browser unloads it
resize|	onresize|	When the visitor resizes the window of the browser
