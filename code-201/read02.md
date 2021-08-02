# TEXT
![img](https://thumbs.dreamstime.com/b/follow-up-die-your-accountant-will-love-you-text-background-word-cloud-concept-follow-up-die-your-accountant-will-love-you-96689445.jpg)

 When creating a web page, you add tags (known as markup) to the contents of the page. These tags provide extra meaning and allow browsers to show users the appropriate structure for the page.

 * Structural markup:
  the elements that you can use to describe both headings and paragraphs.

 * Semantic markup: which provides extra information; such
 as where emphasis is placed in a sentence, that something
 you have written is a quotation (and who said it), the
 meaning of acronyms, and so on.

## 1- Headings

HTML has six "levels" of
headings:

* <**h1**> is used for main headings
* <**h2**> is used for subheadings
* If there are further sections
under the subheadings then the
<**h3**> element is used, and so
on..

## 2- Paragraphs
To create a paragraph, surround
the words that make up the
paragraph with an opening **<p**>
tag and closing <**/p>** tag.

## 3- Bold & Italic
* <**b**>

By enclosing words in the tags
<**b**> and <**/b**> we can make
characters appear bold.

The <**b**> element also represents a section of text that would be presented in a visually different way (for example key words in a paragraph) although the use of
the <**b**> element does not imply any additional meaning.

* <**i**>

By enclosing words in the tags
<**i**> and <**/i**> we can make
characters appear italic.

The <**i**> element also represents a section of text that would be said in a different way from surrounding content — such as technical terms, names of ships, foreign words, thoughts, or other
terms that would usually be
italicized.


## 4- Superscript & Subscrip

<**sup**>

The <**sup**> element is used
to contain characters that
should be superscript such
as the suffixes of dates or
mathematical concepts like
raising a number to a power such
as 2 <sup> 2 .

<**sub**>

The <**sub**> element is used to
contain characters that should
be subscript. It is commonly
used with foot notes or chemical
formulas such as H<sub>2</sub>O.

## 5- White Space

In order to make code easier to
read, web page authors often
add extra spaces or start some
elements on new lines.


When the browser comes across
two or more spaces next to each
other, it only displays one space.

Similarly if it comes across a line
break, it treats that as a single
space too. This is known as
white space collapsing.

## 6- Line Breaks & Horizontal Rules

<**br /**>
As you have already seen, the
browser will automatically show
each new paragraph or heading
on a new line. But if you wanted
to add a line break inside the
middle of a paragraph you can
use the line break tag <**br /**>.

<**hr /**>
To create a break between
themes — such as a change of
topic in a book or a new scene
in a play — you can add a
horizontal rule between sections
using the <**hr /**> tag.

## 7- Visual Editors & Their Code views

***Visual editors*** often resemble
word processors. Although
each editor will differ slightly,
there are some features that
are common to most editors
that allow you to control the
presentation of text.

* Headings are created by
highlighting text then using
a drop-down box to select a
heading.

* Bold and italic text are
created by highlighting some
text and pressing a b or i
button.

* New paragraphs are created
using the return or the enter
key.
* Line breaks are created by
pressing the shift key and the
return key at the same time.

* Horizontal rules are created
using a button with a straight
line on it.


If you copy and paste text from
a program that allows you to
format text (such as Word) into
a visual editor, it may add extra
markup. To prevent this copy
the text into a plain text editor
first (such as Notepad on a PC
or TextEdit on a Mac) and then
copy it from that program and
paste it into the visual editor.


***Code views*** show you the code
created by the visual editor so
you can manually edit it, or so
you can just enter new code
yourself. It is often activated
using a button with an icon
that says HTML or has angled
brackets. White space may be
added to the code by the editor
to make the code easier to read.

## 8- Semantic Markup

you
will meet some more elements
that will help you when you are
adding text to web pages. For
example, you are going to meet
the <***em***> element that allows
you to indicate where emphasis
should be placed on selected
words and the <***blockquote***>
element which indicates that a
block of text is a quotation.


Browsers often display the
contents of these elements in
a different way. For example,
the content of the <***em***>
element is shown in italics,
and a <***blockquote***> is usually
indented. But you should not
use them to change the way that
your text looks; their purpose is
to describe the content of your
web pages more accurately.

The reason for using these
elements is that other programs,
such as screen readers or search
engines, can use this extra
information. For example, the
voice of a screen reader may add
emphasis to the words inside
the <***em***> element, or a search
engine might register that your
page features a quote if you use
the <***blockquote***> element.

## 9- Strong & Emphasis

* <**strong**>

The use of the <**strong**>
element indicates that its
content has strong importance.
For example, the words contained in this element might
be said with strong emphasis.

By default, browsers will show
the contents of a <**strong**>
element in bold.

* <**em**>

The <**em**> element indicates
emphasis that subtly changes
the meaning of a sentence.
By default browsers will show
the contents of an <**em**> element
in italic.

## 10- Quotations

There are two elements
commonly used for marking up
quotations:

<**blockquote**>

The <**blockquote**> element is
used for longer quotes that take
up an entire paragraph. Note
how the <**p**> element is still
used inside the <**blockquote**>
element.

Browsers tend to indent the
contents of the <**blockquote**>
element, however you should not
use this element just to indent a
piece of text — rather you should
achieve this effect using CSS.

<**q**>

The <**q**> element is used for
shorter quotes that sit within
a paragraph. Browsers are
supposed to put quotes around
the <**q**> element, however
Internet Explorer does not —
therefore many people avoid
using the <**q**> element.

## 11- Abbreviations & Acronyms

<**abbr**>

chapter-02/abbreviations.html HTML
If you use an abbreviation or
an acronym, then the <**abbr**>
element can be used. A title
attribute on the opening tag is
used to specify the full term.

## 12- Citations & Definitions

* <**cite**>

When you are referencing a
piece of work such as a book,
film or research paper, the
<**cite**> element can be used
to indicate where the citation is
from.

In HTML5, <**cite**> should not
really be used for a person's
name — but it was allowed in
HTML 4, so most people are
likely to continue to use it.

* <**dfn**>

The first time you explain some
new terminology (perhaps an
academic concept or some
jargon) in a document, it is
known as the defining instance
of it.

The <**dfn**> element is used to
indicate the defining instance of
a new term.



## 13- Author Details
<*address*>

 chapter-02/address.html HTML
The <**address**> element has
quite a specific use: to contain
contact details for the author of
the page.

It can contain a physical address,
but it does not have to. For
example, it may also contain a
phone number or email address.

## 14- Changes to Content

* <**ins**>

* <**del**>

The <**ins**> element can be used
to show content that has been
inserted into a document, while
the <**del**> element can show text
that has been deleted from it.

The content of a <**ins**> element
is usually underlined, while the
content of a <**del**> element
usually has a line through it.

<**s**>

The <**s**> element indicates
something that is no longer
accurate or relevant (but that
should not be deleted).
Visually the content of an <**s**>
element will usually be displayed
with a line through the center.



### Structural markup includes elements such as <**h1**>, <**h2**>, and <**p**>.
Semantic information is carried in elements such as <**cite**> and <**em**>.

## Sumarry

HTML elements are used to describe the structure of
the page (e.g. headings, subheadings, paragraphs).
X They also provide semantic information (e.g. where
emphasis should be placed, the definition of any
acronyms used, when given text is a quotation).

HTML elements are used to describe the structure of
the page (e.g. headings, subheadings, paragraphs).
X They also provide semantic information (e.g. where
emphasis should be placed, the definition of any
acronyms used, when given text is a quotation).
___

# CSS

![img](https://upload.wikimedia.org/wikipedia/commons/thumb/d/d5/CSS3_logo_and_wordmark.svg/1200px-CSS3_logo_and_wordmark.svg.png)

## What is CSS and why it is used?
#### CSS is a markup language that describes the layout and colors of web pages. It can be used to modify the presentation of web pages to fit different devices, such as large screens, small screens, or printers. CSS is independent of HTML and can be used with any XML-based markup language.
---------
## How to Add CSS?

### CSS can be added to HTML documents in 3 ways:

* **Inline**- by using the style attribute inside HTML elements.
* **Internal** - by using a 

* **External** - by using a <link> element to link to an external CSS file.

#### The most common way to add CSS, is to keep the styles in external CSS files. However, in this tutorial we will use inline and internal styles, because this is easier to demonstrate, and easier for you to try it yourself.
---------------
## What is color in CSS?

#### The color CSS property sets the foreground color value of an element's text and text decorations, and sets the <currentcolor> value. currentcolor may be used as an indirect value on other properties and is the default for other color properties, such as border-color 

## How to know CSS color?

#### Probably the most common (yet least intuitive) way to specify colors in CSS is to use their hexadecimal (or hex) values. Hex values are actually just a different way to represent RGB values. Instead of using three numbers between 0 and 255 , you use six hexadecimal numbers. Hex numbers can be 0-9 and A-F 

------
## What is CSS reference and how to use it?
### Cascading Style Sheets
#### Use this CSS reference to browse an alphabetical index of all of the standard CSS properties, pseudo-classes, pseudo-elements, data types, functional notations and at-rules. You can also browse key CSS concepts and a list of selectors organized by type.
-----
## What is Reset CSS?

#### A CSS Reset (or “Reset CSS”) is a short, often compressed (minified) set of CSS rules that resets the styling of all HTML elements to a consistent baseline. In case you didn't know, every browser has its own default 'user agent' stylesheet, that it uses to make unstyled websites appear more legible.

#### The goal of a reset stylesheet is to reduce browser inconsistencies in things like default line heights, margins and font sizes of headings, and so on.
#### Reset styles quite often appear in CSS frameworks, and the original "meyerweb reset" found its way into Blueprint, among others.

