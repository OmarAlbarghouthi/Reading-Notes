# **HTML Tables; JS Constructor Functions**

## **What's a Table?**

A table represents information in a grid format. Examples of tables include financial reports, TV
schedules, and sports results.

### **Basic Table Structure**

* ## <**table**>

The <**table**> element is used
to create a table. The contents
of the table are written out row
by row.

* ## <**tr**>

You indicate the start of each
row using the opening <**tr**> tag.
(The **tr** stands for table row.)

It is followed by one or more
<**td**> elements (one for each cell in that row).

At the end of the row you use a
closing </**tr**> tag.

* ## <**td**>
Each cell of a table is
represented using a <**td**>
element. (The **td** stands for
table data.)

At the end of each cell you use a
closing </**td**> tag.
___

### **Table Headings**

## <**th**>

The <**th**> element is used just
like the <**td**> element but its
purpose is to represent the
heading for either a column or
a row. (The th stands for table
heading.)

Even if a cell has no content,
you should still use a <**td**> or
<**th**> element to represent
the presence of an empty cell
otherwise the table will not
render correctly. (The first cell
in the first row of this example
shows an empty cell.)

Using <**th**> elements for
headings helps people who
use screen readers, improves
the ability for search engines
to index your pages, and also
enables you to control the
appearance of tables better
when you start to use CSS.

You can use the scope attribute
on the <**th**> element to indicate
whether it is a heading for a
column or a row. It can take the
values: row to indicate a heading
for a row or col to indicate a
heading for a column.

___

### **Spanning Columns**

Sometimes you may need the
entries in a table to stretch
across more than one column.

The colspan attribute can be
used on a <**th**> or <**td**> element and indicates how many columns that cell should run across.

### **Spanning Rows**

You may also need entries in
a table to stretch down across
more than one row.

The rowspan attribute can be
used on a <**th**> or <**td**> element to indicate how many rows a cell should span down the table.

___

## **Long Tables**

There are three elements that
help distinguish between the
main content of the table and
the first and last rows (which can
contain different content).

These elements help people
who use screen readers and also
allow you to style these sections
in a different manner than the
rest of the table (as you will see
when you learn about CSS).

* <**thead**>

The headings of the table should
sit inside the <**thead**> element.

* <**tbody**>

The body should sit inside the
<**tbody**> element.

* <**tfoot**>

The footer belongs inside the
<**tfoot**> element.

___
___

# **JS Functions, Objects**

![img](https://res.cloudinary.com/academind-gmbh/image/upload/f_auto,q_auto/c_fit,dpr_3.0,g_center,w_500/v1/academind.com/content/tutorials/javascript-functions-are-objects/functions-are-objects)

## **JavaScript Functions are Objects!**

*Yes, in JS world a function is considered an object.*

**Types in JavaScript are categorized by:**

* **Primitives** (string, number, null, boolean, undefined, symbol):

these are immutable data types. They are not objects, don’t have methods and they are stored in memory by value.

* **Non-Primitives** (functions, arrays and objects):

these are mutable data types. They are objects and they are stored in memory by reference.



### **Why are functions logged as Function (and not as “Object” or something similar)?**

Well, it’s because functions are not just objects, they are Function objects, meaning that besides being able to assign properties and methods to them, they also have properties and methods already defined by the built-in Function object.

### **And what is a built-in object?** 

In JS there are standard built-in objects upon which other objects are based. Said this, the standard built-in Function is the object upon which functions are based.

The built-in Function object has properties like name, length and has methods like call, apply and bind.





