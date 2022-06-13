# Day 2

## HTML elements
An HTML element is defined by a start tag, some content, and an end tag.

The HTML element is everything from the start tag to the end tag:

<tagname>Content goes here...</tagname>

Examples of some HTML elements:

Start tag	Element content	End tag

<h1>	My First Heading     </h1>
<p>  	My first paragraph   </p>
<br>	     none	          none

Note: Some HTML elements have no content (like the <br> element). These elements are called empty elements. Empty elements do not have an end tag!

## Nested HTML elements

HTML elements can be nested (this means that elements can contain other elements).

All HTML documents consist of nested HTML elements.

The following example contains four HTML elements (<html>, <body>, <h1> and <p>):

Example

<!DOCTYPE html>
<html>
<body>

<h1>My First Heading</h1>
<p>My first paragraph.</p>

</body>
</html>

Example Explained

The <html> element is the root element and it defines the whole HTML document.

It has a start tag <html> and an end tag </html>.

Then, inside the <html> element there is a <body> element:

<body>

<h1>My First Heading</h1>
<p>My first paragraph.</p>

</body>
The <body> element defines the document's body.

It has a start tag <body> and an end tag </body>.

Then, inside the <body> element there are two other elements: <h1> and <p>:

<h1>My First Heading</h1>
<p>My first paragraph.</p>

The <h1> element defines a heading.

It has a start tag <h1> and an end tag </h1>:

<h1>My First Heading</h1>

The <p> element defines a paragraph.

It has a start tag <p> and an end tag </p>:

<p>My first paragraph.</p>

## Never Skip the End Tag

Some HTML elements will display correctly, even if you forget the end tag:

Example

<p>This is a paragraph
<p>This is a paragraph

However, never rely on this! Unexpected results and errors may occur if you forget the end tag!

## Empty HTML Elements

HTML elements with no content are called empty elements.

The <br> tag defines a line break, and is an empty element without a closing tag:

Example

<p>This is a <br> paragraph with a line break.</p>HTML is Not Case Sensitive

## HTML tags are not case sensitive:

 <P> means the same as <p>.

The HTML standard does not require lowercase tags, but W3C recommends lowercase in HTML, and demands lowercase for stricter document types like XHTML.
## HTML Tag Reference

<html>	Defines the root of an HTML document
<body>	Defines the document's body
<h1> to <h6>	Defines HTML headings

## HTML Attributes

All HTML elements can have attributes
Attributes provide additional information about elements
Attributes are always specified in the start tag
Attributes usually come in name/value pairs like: name="value"

## The href Attribute

The <a> tag defines a hyperlink. The href attribute specifies the URL of the page the link goes to:

Example

<a href="https://www.w3schools.com">Visit W3Schools</a>

## The src Attribute

The <img> tag is used to embed an image in an HTML page. The src attribute specifies the path to the image to be displayed:

Example

<img src="img_girl.jpg">

There are two ways to specify the URL in the src attribute:

1. Absolute URL - Links to an external image that is hosted on another website. Example: src="https://www.w3schools.com/images/img_girl.jpg".

Notes: External images might be under copyright. If you do not get permission to use it, you may be in violation of copyright laws. In addition, you cannot control external images; it can suddenly be removed or changed.

2. Relative URL - Links to an image that is hosted within the website. Here, the URL does not include the domain name. If the URL begins without a slash, it will be relative to the current page. Example: src="img_girl.jpg". If the URL begins with a slash, it will be relative to the domain. Example: src="/images/img_girl.jpg".

Tip: It is almost always best to use relative URLs. They will not break if you change domain.

## The width and height Attributes

The <img> tag should also contain the width and height attributes, which specifies the width and height of the image (in pixels):

Example

<img src="img_girl.jpg" width="500" height="600">

## The alt Attribute

The required alt attribute for the <img> tag specifies an alternate text for an image, if the image for some reason cannot be displayed. This can be due to slow connection, or an error in the src attribute, or if the user uses a screen reader.

Example

<img src="img_girl.jpg" alt="Girl with a jacket">

Example

See what happens if we try to display an image that does not exist:

<img src="img_typo.jpg" alt="Girl with a jacket">

## The style Attribute

The style attribute is used to add styles to an element, such as color, font, size, and more.

Example

<p style="color:red;">This is a red paragraph.</p>

## The lang Attribute

You should always include the lang attribute inside the <html> tag, to declare the language of the Web page. This is meant to assist search engines and browsers.

The following example specifies English as the language:

<!DOCTYPE html>
<html lang="en">
<body>
...
</body>
</html>

Country codes can also be added to the language code in the lang attribute. So, the first two characters define the language of the HTML page, and the last two characters define the country.

The following example specifies English as the language and United States as the country:

<!DOCTYPE html>
<html lang="en-US">
<body>
...
</body>
</html>

## The title Attribute

The title attribute defines some extra information about an element.

The value of the title attribute will be displayed as a tooltip when you mouse over the element:

Example

<p title="I'm a tooltip">This is a paragraph.</p>

In some situations, when the attribute value itself contains double quotes, it is necessary to use single quotes:

<p title='John "ShotGun" Nelson'>

Or vice versa:

<p title="John 'ShotGun' Nelson">

# Chapter Summary

All HTML elements can have attributes
The href attribute of <a> specifies the URL of the page the link goes to
The src attribute of <img> specifies the path to the image to be displayed
The width and height attributes of <img> provide size information for images
The alt attribute of <img> provides an alternate text for an image
The style attribute is used to add styles to an element, such as color, font, size, and more
The lang attribute of the <html> tag declares the language of the Web page
The title attribute defines some extra information about an element
# HTML Headings

HTML headings are titles or subtitles that you want to display on a webpage.

Example

Heading 1
Heading 2
Heading 3
Heading 4
Heading 5
Heading 6

1>6 (in size)

