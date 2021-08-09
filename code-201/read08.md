# **CSS Layout**
![img](https://d2eip9sf3oo6c2.cloudfront.net/tags/images/000/000/175/square_480/csslang.png)

## **Layout**

## **Key Concepts in Positioning Elements**


### **Building Blocks**


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

### **Relative Positioning position:relative**

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
