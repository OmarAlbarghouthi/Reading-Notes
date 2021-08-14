# **Images & Practical Information**

<img src="https://www.epfl.ch/campus/events/wp-content/uploads/2019/09/iStock-1133842270-1536x864.jpg" alt="" width="900" height = "300"/>

## **Images**
___
> ### **Controlling size of images in CSS**

Controlling the size and alignment of
your images using CSS keeps rules that
affect the presentation of your page in
the CSS and out of the HTML markup.

You can also achieve several interesting effects using
background images. In this chapter you will learn how to:

* Specify the size and alignment of an image using.

* Add background images to boxes.

* Create image rollovers in CSS.

You can control the size of an
image using the width and
height properties in CSS, just
like you can for any other box.

Specifying image sizes helps
pages to load more smoothly
because the HTML and CSS
code will often load before the
images, and telling the browser
how much space to leave for an
image allows it to render the rest
of the page without waiting for
the image to download.

You might think that your site
is likely to have images of all
different sizes, but a lot of sites
use the same sized image across
many of their pages. 

___
> ### **Alligning images using CSS**

In the last chapter, you saw how
the float property can be used
to move an element to the left or
the right of its containing block,
allowing text to flow around it.

Rather than using the <img>
element's align attribute, web
page authors are increasingly
using the float property to align
images. There are two ways that
this is commonly achieved:

**1:** The float property is added
to the class that was created to
represent the size of the image.


**2:** New classes are created with
names such as align-left or
align-right to align the images
to the left or right of the page.
These class names are used in
addition to classes that indicate
the size of the image.

___
> ### **Centering images Using CSS**

By default, images are inline elements. This means that they flow within the surrounding text. In order to center an image, it should be turned into a blocklevel element using the display property with a value of block.

Once it has been made into a
block-level element, there are
two common ways in which you
can horizontally center an image:

**1:** On the containing element,
you can use the text-align
property with a value of center.

**2:** On the image itself, you can
use the use the margin property
and set the values of the left and
right margins to auto.

You can specify class names
that allow any element to be
centered, in the same way that
you can for the dimensions or
alignment of images.
___

> ### **Background Images**

The background-image
property allows you to place
an image behind any HTML
element. This could be the entire
page or just part of the page. By
default, a background image will
repeat to fill the entire box.

The path to the image follows
the letters url, and it is put
inside parentheses and quotes.
___

> ### **Repeating Images

**background-repeat**

 **background-attachment**


 The background-repeat property can have four values:

* **repeat**

The background image is
repeated both horizontally and
vertically (the default way it
is shown if the backgroundrepeat property isn't used).

* **repeat-x**

The image is repeated
horizontally only (as shown in
the first example on the left).
repeat-y
The image is repeated vertically
only.

* **no-repeat**

The image is only shown once.
The background-attachment
property specifies whether a
background image should stay in
one position or move as the user
scrolls up and down the page. It
can have one of two values:

* **fixed**

The background image stays in
the same position on the page.

* **scroll**

The background image moves
up and down as the user scrolls
up and down the page.
___

> ### **Background Position**

When an image is not being
repeated, you can use the
background-position
property to specify where in the
browser window the background
image should be placed.

This property usually has a pair
of values. The first represents
the horizontal position and the
second represents the vertical.

 * left top
 * left center
 * left bottom
 * center top
 * center center
 * center bottom
 * right top
 * right center
 * right bottom

If you only specify one value,
the second value will default to
center.

You can also use a pair of pixels
or percentages. These represent
the distance from the top left
corner of the browser window
(or containing box). The top left
corner is equal to 0% 0%. The
example shown, with values of
50% 50%, centers the image
horizontally and vertically.
___
___
___

# **Practical Information**


> ### **Search Engine Optimization (SEO)**

SEO is a huge topic and several books have been written on the subject.
The following pages will help you understand the key concepts so you can
improve your website's visibility on search engines.

* **The Basics**

Search engine optimization (or
SEO) is the practice of trying
to help your site appear nearer
the top of search engine results
when people look for the topics
that your website covers.

At the heart of SEO is the idea of
working out which terms people
are likely to enter into a search
engine to find your site and then
using these terms in the right
places on your site to increase
the chances that search engines
will show a link to your site in
their results.

* **On-Page Techniques**

On-page techniques are the
methods you can use on your
web pages to improve their
rating in search engines.

The main component of this is
looking at keywords that people
are likely to enter into a search
engine if they wanted to find
your site, and then including
these in the text and HTML code
for your site in order to help the
search engines know that your
site covers these topics.

* **Off-Page Techniques**

Getting other sites to link to you
is just as important as on-page
techniques. Search engines help
determine how to rank your
site by looking at the number of
other sites that link to yours.

They are particularly interested
in sites whose content is related
to yours. For example, if you
were running a website that
sold fish bait, then a link from
a hairdresser is not likely to be
considered as relevant as one
from an angling community

___

> ### **On-Page SEO**

In every page of your website there are seven key places where keywords
(the words people might search on to find your site) can appear in order
to improve its findability.

**1: Page Title**


The page title appears at the top
of the browser window or on the
tab of a browser. It is specified in
the <**title**> element which lives
inside the <**head**> element.

**2: URL / Web Address**

The name of the file is part of
the URL. Where possible, use
keywords in the file name.

**3: Headings**

If the keywords are in a heading
<**hn**> element then a search
engine will know that this page is
all about that subject and give it
greater weight than other text.

**4: Text**

Where possible, it helps to
repeat the keywords in the main
body of the text at least 2-3
times. Do not, however, over-use
these terms, because the text
must be easy for a human to
read.

**5: Link Text**

Use keywords in the text that
create links between pages
(rather than using generic
expressions such as "click here").

**6: Image Alt Text**

Search engines rely on you
providing accurate descriptions
of images in the alt text. This
will also help your images show
up in the results of image-based
searches.

**7: Page Descriptions**

The description also lives inside
the <**head**> element and is
specified using a <**meta**> tag.
It should be a sentence that
describes the content of the
page. (These are not shown in
the browser window but they
may be displayed in the results
pages of search engines.)

Never try to fool search engines!
They will penalize you for it. For
example, never add text in the
same color as the background of
the page as they can detect this.

