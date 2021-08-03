# **HTML Links, CSS Layout, JS Functions**

## **Links**
Links are the defining feature of the web
because they allow you to move from
one web page to another — enabling the
very idea of browsing or surfing.

You will commonly come across the following types of links:

* Links from one website to another
* Links from one page to another on the same website
* Links from one part of a web page to another part of the same page.
* Links that open in a new browser window
* Links that start up your email program and address a new email to someone.

### **Writing Links**
Links are created using the **<a<a>>**</a> element. Users can click on anything
between the opening **<a<a>>**</a> tag and the closing
 **<a</a>>** tag. You specify which page you want to link to using the href attribute.


 ### **Linking to Other Sites**

**<<a>a>**</a> chapter-04/linking-to-other-sites.html HTML
Links are created using the **<<a>a>**</a>
element which has an attribute
called href. The value of the
href attribute is the page that
you want people to go to when
they click on the link.

Users can click on anything that
appears between the opening
**<a<a>>**</a> tag and the closing **<a</a>>**
tag and will be taken to the page
specified in the href attribute.
When you link to a different
website, the value of the href
attribute will be the full web
address for the site, which is
known as an absolute URL.

### **Absolute URLs**

URL stands for Uniform
Resource Locator. Every web
page has its own URL. This is the
web address that you would type
into a browser if you wanted to
visit that specific page.


An absolute URL starts with
the domain name for that site,
and can be followed by the path
to a specific page. If no page is
specified, the site will display the
homepage.

### **Linking to Other Pages on the Same Site**

**<<a>a>**</a>


When you are linking to other
pages within the same site,
you do not need to specify the
domain name in the URL. You
can use a shorthand known as a
relative URL.

If all the pages of the site are in
the same folder, then the value
of the href attribute is just the
name of the file.

If you have different pages of a
site in different folders, then you
can use a slightly more complex
syntax to indicate where the
page is in relation to the current
page. You will learn more about
these on the pages 81-84.

If you look at the download
code for each chapter, you will
see that the index.html file
contains links that use relative
URLs.


### **Email Links**

mailto: chapter-04/email-links.html HTML
To create a link that starts up
the user's email program and
addresses an email to a specified
email address, you use the <**a**></a>
element. However, this time the
value of the href attribute starts
with mailto: and is followed by
the email address you want the
email to be sent to.


On the right you can see that
an email link looks just like any
other link but, when it is clicked
on, the user's email program
will open a new email message
and address it to the person
specified in the link.
_______

# **Layout**

### **Key Concepts in Positioning Elements**


## **Building Blocks**


CSS treats each HTML element as if it is in its
own box. This box will either be a block-level
box or an inline box.

Block-level boxes start on a new line and act as the main building blocks
of any layout, while inline boxes flow between surrounding text.
You can control how much space each box takes up by setting the width of the
boxes (and sometimes the height, too). To separate boxes, you can use borders, margins, padding, and background colors. 

* **Block-level** elements
start on a new line
Examples include:
<**h1**> <**p**> <**ul**> <**li**>

* **Inline elements**
flow in between
surrounding text
Examples include:
<**img**> <**b**> <**i**>

## **Relative Positioning position:relative**

Relative positioning moves an
element in relation to where it
would have been in normal flow.
For example, you can move it 10
pixels lower than it would have
been in normal flow or 20% to
the right.

You can indicate that an element
should be relatively positioned
using the position property
with a value of relative.

You then use the offset
properties (top or bottom and
left or right) to indicate how
far to move the element from
where it would have been in
normal flow.

To move the box up or down,
you can use either the top or
bottom properties.

To move the box horizontally,
you can use either the left or
right properties.

The values of the box offset
properties are usually given in
pixels, percentages or ems.

## **Absolute Positioning**
### position:absolute

When the position property
is given a value of absolute,
the box is taken out of normal
flow and no longer affects the
position of other elements on
the page. (They act like it is not
there.)

The box offset properties (top
or bottom and left or right)
specify where the element
should appear in relation to its
containing element.

In this example, the heading has
been positioned at the top of the
page and 500 pixels from its left
edge. The width of the heading is
set to be 250 pixels wide.

The width property has
also been applied to the <**p**>
elements in this example
to prevent the text from
overlapping and becoming
unreadable.

_____

# **JS**

## **What are JavaScript functions?**

A function in JavaScript is similar to a procedure—a set of statements that performs a task or calculates a value, but for a procedure to qualify as a function, it should take some input and return an output where there is some obvious relationship between the input and the output.

### **Function Expression:**
A Function Expressions defines a named or anonymous function. An anonymous function is a function that has no name.

### **Arrow Function:**

An Arrow Function Expression is a shorter syntax for writing function expressions. Arrow functions do not create their own value.

We can write the arrow function in multiple ways:

* **First:**

it just looks like a regular function expression but have arrow (=>) key.

**const double = (value) => {**

 **return value * 2**
**}**

**double(10); // 20**

* **Second:**

Omit the return keyword

**const double2 = value => value * 2;**

**double2(10); // 20**


* **Third:**

If our function have no parameter

**const noise = () => console.log("Pling");**

**noise(); // Pling**

## **OR**

**const noise2 = _ => console.log("Pling");**

**noise2(); // Pling**


* **Fifth:**

We can use default value in our parameters

**const multiply = (a = 2, b = 3, c = 1) => a * b * c;**

**multiply(2, 2, 2); // 8**

**multiply(2, 2);    // 4**

**multiply(3);       // 9**

**multiply();        // 6**


JavaScript is extremely broad-minded about the number of arguments you pass to a function. If you pass too many, the extra ones are ignored. If you pass too few, the missing parameters get assigned the value undefined.

## **Pair Programming**


### **How does pair programming work?**
While there are many different styles, pair programming commonly involves two roles: the Driver and the Navigator. The Driver is the programmer who is typing and the only one whose hands are on the keyboard. Handling the “mechanics” of coding, the Driver manages the text editor, switching files, version control, and—of course writing—code. The Navigator uses their words to guide the Driver but does not provide any direct input to the computer. The Navigator thinks about the big picture, what comes next, how an algorithm might be converted in to code, while scanning for typos or bugs. The Navigator might also utilize their computer as a second screen to look up solutions and documentation, but should not be writing any code.


### **Why pair program?**
While learning to code, developers likely study several programming languages. Similar to a foreign language class, there are four fundamental skills that help anyone learn a new language: Listening: hearing and interpreting the vocabulary Speaking: using the correct words to communicate an idea Reading: understanding what written language intends to convey Writing: producing from scratch a meaningful





