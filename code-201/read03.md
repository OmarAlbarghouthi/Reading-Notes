# HTML Lists, Control Flow with JS, and the CSS Box Model

## HTML Lists

*  **Ordered lists** are lists where each item in the list is
numbered. For example, the list might be a set of steps for
a recipe that must be performed in order, or a legal contract
where each point needs to be identified by a section
number.

*  **Unordered lists** are lists that begin with a bullet point
(rather than characters that indicate order).

* **Definition lists** are made up of a set of terms along with the
definitions for each of those terms


### Ordered lists

* **<ol>**
The ordered list is created with
the **<ol>** element.

* **<li>**
Each item in the list is placed
between an opening **<li>** tag
and a closing **</li>** tag. (The li
stands for list item.)

### Unordered lists

* **<ul>**

The unordered list is created
with the **<ul>** element.

* **<li>**

Each item in the list is placed
between an opening **<li>** tag
and a closing **</li>** tag. (The li
stands for list item.)

### Definition Lists

* **<dl>**

The definition list is created with
the **<dl>** element and usually
consists of a series of terms and
their definitions.

Inside the **<dl>** element you will
usually see pairs of **<dt>** and
**<dd>** elements.

**<dt>**

This is used to contain the term
being defined (the definition
term).

**<dd>**

This is used to contain the
definition.


### Nested Lists

You can put a second list inside
an **<li>**element to create a sublist or nested list.
Browsers display nested lists
indented further than the parent
list. 

In nested unordered lists,
the browser will usually change
the style of the bullet point too


# CSS box model

### What is the use of the box model in CSS?

The CSS Box Model is used to create a definition for the way the HTML elements are organized on the screen. This approach accounts for options such as margins, padding, borders, and all the properties that manipulate them. Each element can be thought of as having its own box.

### Box Dimensions

#### width, height

By default a box is sized just big
enough to hold its contents. To
set your own dimensions for a
box you can use the height and
width properties.

The most popular ways to
specify the size of a box are
to use pixels, percentages, or
ems. Traditionally, pixels have
been the most popular method
because they allow designers to
accurately control their size.

When you use percentages,
the size of the box is relative to
the size of the browser window
or, if the box is encased within
another box, it is a percentage of
the size of the containing box.

When you use ems, the size
of the box is based on the size
of text within it. Designers
have recently started to use
percentages and ems more for
measurements as they try to
create designs that are flexible
across devices which have
different-sized screens.

In the example on the right, you
can see that a containing **<div>**
element is used which is 300
pixels wide by 300 pixels high.
Inside of this is a paragraph
that is 75% of the width and
height of the containing element.
This means that the size of the
paragraph is 225 pixels wide by
225 pixels high.

### Limiting Width
#### min-width, max-width

Some page designs expand and
shrink to fit the size of the user's
screen. In such designs, the
min-width property specifies
the smallest size a box can be
displayed at when the browser
window is narrow, and the
max-width property indicates
the maximum width a box can
stretch to when the browser
window is wide.

These are very helpful properties
to ensure that the content of
pages are legible (especially on
the smaller screens of handheld
devices). For example, you can
use the max-width property to
ensure that lines of text do not
appear too wide within a big
browser window and you can
use the min-width property
to make sure that they do not
appear too narrow.

You may find it helpful to try this
example out in your browser so
that you can see what happens
when you increase or decrease
the size of the browser window.

Please note that these properties
were first supported in IE7 and
Firefox 2 so they will not work in
older versions of these browsers.

### Limiting Height
#### min-height, max-height
In the same way that you might
want to limit the width of a box
on a page, you may also want
to limit the height of it.

This is achieved using the min-height
and max-height properties.
The example on this page
demonstrates these properties
in action. It also shows you what
happens when the content of the
box takes up more space than
the size specified for the box.

If the box is not big enough to
hold the content, and the content
expands outside the box it can
look very messy. To control
what happens when there is not
enough space for the content of
a box, you can use the overflow
property, which is discussed on
the next page.

### Overflowing Content
#### overflow

The overflow property tells the
browser what to do if the content
contained within a box is larger
than the box itself. It can have
one of two values:

#### hidden

This property simply hides any
extra content that does not fit in
the box.

#### scroll

This property adds a scrollbar to
the box so that users can scroll
to see the missing content.
On the left, you can see two
boxes whose contents expand
beyond their set dimensions. The
first example has the overflow
property with a value of hidden.
The second example has the
overflow property with a value
of scroll.


The overflow property is
particularly handy because some
browsers allow users to adjust
the size of the text to appear as
large or as small as they want. If
the text is set too large then the
page can become an unreadable
mess. Hiding the overflow on
such boxes helps prevent items
overlapping on the page.



# JS

## Array 

An array is a special type of variable. It doesn't 
just store one value; it stores a list of values. 
You should consider using an 
array whenever you are working 
with a list or a set of values that 
are related to each other.

Arrays are especially helpful 
when you do not know how 
many items a list will contain 
because, when you create the 
array, you do not need to specify 
how many values it will hold.

If you don't know how many 
items a list will contain, rather 
than creating enough variables 
for a long list (when you might 
only use a small percentage 
of them), using an array is 
considered a better solution. 
For example, an array can be 
suited to storing the individual 
items on a shopping list because 
it is a list of related items. 

Additionally, each time you write 
a new shopping list, the number 
of items on it may differ. 
As you will see on the next page, 
values in an array are separated 
by commas. 

In Chapter 12, you will see that 
arrays can be very helpful when 
representing complex data.



## CREATING AN ARRAY
You create an array and give it 
a name just like you would any 
other variable (using the var 
keyword followed by the name of 
the array). 

The values are assigned to the 
array inside a pair of square 
brackets, and each value is 
separated by a comma.

The values in the array do not need 
to be the same data type, so you 
can store a string, a number and 
a Boolean all in the same array. 

This technique for creating 
an array is known as an array 
literal. It is usually the preferred 
method for creating an array. 

You can also write each value on 
a separate line: 

colors= ['white', 
'black', 
'custom'];

On the left, you can see an 
array created using a different 
technique called an array 
constructor. 

This uses the new 
keyword followed by Array(); 
The values are then specified 
in parentheses (not square 
brackets), and each value is 
separated by a comma. You can 
also use a method called i tern() 
to retrieve data from the array. 
(The index number of the item is 
specified in the parentheses.) 


## ACCESSING & CHANGING VALUES IN AN ARRAY

The first lines of code on the left 
create an array containing a list 
of three colors. (The values can 
be added on the same line or on 
separate lines as shown here.)

Having created the array, the 
third item on the list is changed 
from 'custom' to 'beige'. 

To access a value from an array, 
after the array name you specify 
the index number for that value 
inside square brackets. 

You can change the value of an 
item an array by selecting it and 
assigning it a new value just as 
you would any other variable 
(using the equals sign and the 
new value for that item). 

In the last two statements, the 
newly updated third item in the 
array is added to the page. 

If you wanted to write out all of 
the items in an array, you would 
use a loop, which you will meet 
on p170. 


