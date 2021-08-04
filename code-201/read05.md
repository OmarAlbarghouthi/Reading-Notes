# **HTML Images, CSS Color & Text**

## **IMAGES**

![img](https://community-cdn-digitalocean-com.global.ssl.fastly.net/variants/hNQEpv1uR5UdRen5xP9Cjxez/035575f2985fe451d86e717d73691e533a1a00545d7230900ed786341dc3c882)

A picture can say a thousand words, and great
images help make the difference between an
average-looking site and a really engaging one.

Images can be used to set the
tone for a site in less time than
it takes to read a description. If
you do not have photographs
to use on your website, there
are companies who sell stock
images; these are images you
pay to use (there is a list of stock
photography websites below).

Remember that all images are
subject to copyright, and you
can get in trouble for simply
taking photographs from
another website.

### **Storing Images on Your Site**

If you are building a site from scratch, it is good
practice to create a folder for all of the images
the site uses.

### **Adding Images**
<**img**>

chapter-05/adding-images.html HTML
To add an image into the page
you need to use an <**img**>
element. This is an empty
element (which means there is
no closing tag). It must carry the
following two attributes:


#### **src**

This tells the browser where
it can find the image file. This
will usually be a relative URL
pointing to an image on your
own site. (Here you can see that
the images are in a child folder
called images — relative URLs
were covered on pages 83-84).

#### **alt**

This provides a text description
of the image which describes the
image if you cannot see it.

#### **title**

You can also use the title
attribute with the <**img**> element
to provide additional information
about the image. Most browsers
will display the content of this
attribute in a tootip when the
user hovers over the image.


### **Three Rules for Creating Images**

There are three rules to remember when you
are creating images for your website which are
summarized below. We go into greater detail
on each topic over the next nine pages.

1- **Save images in the right format**
 
Websites mainly use images in jpeg, gif, or png format. If you choose the wrong image format then your image might not look as sharp as it should and can make the web page slower to load.

2- **Save images at the right size**

You should save the image at
the same width and height it will
appear on the website. If
the image is smaller than the
width or height that you have
specified, the image can be
distorted and stretched. If the
image is larger than the width
and height if you have specified,
the image will take longer to
display on the page.

3- **Use the correct resolution**

Computer screens are made up
of dots known as pixels. Images
used on the web are also made
up of tiny dots. Resolution refers
to the number of dots per inch,
and most computer screens only
show web pages at 72 pixels
per inch. So saving images at
a higher resolution results in
images that are larger than
necessary and take longer to
download.

___

# CSS Color
## **Color can really bring your pages to life**

### **Foreground Color**


#### **color**
The color property allows you
to specify the color of text inside
an element. You can specify any
color in CSS in one of three ways:

#### **rgb values**

These express colors in terms
of how much red, green and
blue are used to make it up. For
example: rgb(100,100,90).

#### **hex codes**
These are six-digit codes that
represent the amount of red,
green and blue in a color,
preceded by a pound or hash #
sign. For example: #ee3e80.

#### **color names**

There are 147 predefined color
names that are recognized
by browsers. For example: DarkCyan

We look at these three different
ways of specifying colors on the
next double-page spread.

### **Background Color**

#### **background-color**
CSS treats each HTML element
as if it appears in a box, and the
background-color property
sets the color of the background
for that box.

You can specify your choice of
background color in the same
three ways you can specify
foreground colors: RGB values,
hex codes, and color names
(covered on the next page).

If you do not specify a
background color, then the
background is transparent.

By default, most browser
windows have a white
background, but browser users
can set a background color for
their windows, so if you want
to be sure that the background
is white you can use the
background-color property on
the <**body**> element.

## **CSS3: Opacity**

### **opacity, rgba**

CSS3 introduces the opacity
property which allows you to
specify the opacity of an element
and any of its child elements.
The value is a number between
0.0 and 1.0 (so a value of 0.5
is 50% opacity and 0.15 is 15%
opacity).

The CSS3 rgba property allows
you to specify a color, just like
you would with an RGB value,
but adds a fourth value to
indicate opacity. This value is
known as an alpha value and is
a number between 0.0 and 1.0
(so a value of 0.5 is 50% opacity
and 0.15 is 15% opacity). The
rgba value will only affect the
element on which it is applied
(not child elements).

Because some browsers will
not recognize RGBA colors, you
can offer a fallback so that they
display a solid color. If there are
two rules that apply to the same
element, the latter of the two
will take priority. To create the
fallback, you can specify a color
as a hex code, color name or
RGB value, followed by the rule
that specifies an RGBA value. If
the browser understands RGBA
colors it will use that rule. If it
doesn't, it will use the RGB value.
___
# **CSS Text**

## **TEXT**
The properties that allow you to control
the appearance of text can be split into
two groups:

● Those that directly affect the font and its appearance (including the typeface, whether it is regular, bold or italic, and the size of the text).

● Those that would have the same effect on text no matter what font you were using (including the color of text and the spacing between words and letters).

### **Typeface Terminology**

* **Serif**

Serif fonts have extra details on
the ends of the main strokes of
the letters. These details are
known as serifs.

In print, serif fonts were
traditionally used for long
passages of text because they
were considered easier to read.


* **Sans-Serif**

Sans-serif fonts have straight
ends to letters, and therefore
have a much cleaner design.

Screens have a lower resolution
than print. So, if the text is small,
sans-serif fonts can be clearer
to read.

* **Monospace**
Every letter in a monospace (or
fixed-width) font is the same
width. (Non-monospace fonts
have different widths.)

Monospace fonts are commonly
used for code because they align
nicely, making the text easier to
follow.

### **Specifying Typefaces**

####  **font-family**

The font-family property
allows you to specify the
typeface that should be used for
any text inside the element(s) to
which a CSS rule applies.

The value of this property is the
name of the typeface you want
to use.

The people who are visiting
your site need the typeface you
have specified installed on their
computer in order for it to be
displayed.

You can specify a list of fonts
separated by commas so that,
if the user does not have your
first choice of typeface installed,
the browser can try to use an
alternative font from the list.
It is also common to end with a
generic font name for that type
of font (which you saw on pages
269-270).

If a font name is made up of
more than one word, it should be
put in double quotes.
Designers suggest pages usually
look better if they use no more
than three typefaces on a page.



### **Size of Type**

 #### **font-size**

The font-size property enables
you to specify a size for the
font. There are several ways to
specify the size of a font. The
most common are:

*  **pixels**

Pixels are commonly used
because they allow web
designers very precise control
over how much space their text
takes up. The number of pixels is
followed by the letters px.


* **percentages**

The default size of text in
browsers is 16px. So a size of
75% would be the equivalent of
12px, and 200% would be 32px.
If you create a rule to make all
text inside the <**body**> element
to be 75% of the default size (to
make it 12px), and then specify
another rule that indicates the
content of an element inside the
<**body**> element should be 75%
size, it will be 9px (75% of the
12px font size).

* **ems**

An em is equivalent to the width
of a letter m.

