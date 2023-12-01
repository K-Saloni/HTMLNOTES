#HTML Attributes
HTML attributes provide additional information about HTML elements.

HTML Attributes
All HTML elements can have attributes
Attributes provide additional information about elements
Attributes are always specified in the start tag
Attributes usually come in name/value pairs like: name="value"
The href Attribute
The <a> tag defines a hyperlink. The href attribute specifies the URL of the page the link goes to:

Example
<a href="https://www.google.com">Visit visit google</a>
You will learn more about links in our HTML Links chapter.

The src Attribute
The <img> tag is used to embed an image in an HTML page. The src attribute specifies the path to the image to be displayed:

Example
<img src="img_girl.jpg">
There are two ways to specify the URL in the src attribute:

1. Absolute URL - Links to an external image that is hosted on another website. Example: src="https://www.google.com/images/img_girl.jpg".

Notes: External images might be under copyright. If you do not get permission to use it, you may be in violation of copyright laws. In addition, you cannot control external images; it can suddenly be removed or changed.

2. Relative URL - Links to an image that is hosted within the website. Here, the URL does not include the domain name. If the URL begins without a slash, it will be relative to the current page. Example: src="img_girl.jpg". If the URL begins with a slash, it will be relative to the domain. Example: src="/images/img_girl.jpg".

Tip: It is almost always best to use relative URLs. They will not break if you change domain.

The width and height Attributes
The <img> tag should also contain the width and height attributes, which specify the width and height of the image (in pixels):

Example
<img src="img_girl.jpg" width="500" height="600">
The alt Attribute
The required alt attribute for the <img> tag specifies an alternate text for an image, if the image for some reason cannot be displayed. This can be due to a slow connection, or an error in the src attribute, or if the user uses a screen reader.

Example
<img src="img_girl.jpg" alt="Girl with a jacket">
Example
See what happens if we try to display an image that does not exist:

<img src="img_typo.jpg" alt="Girl with a jacket">
You will learn more about images in our HTML Images chapter.

The style Attribute
The style attribute is used to add styles to an element, such as color, font, size, and more.

Example
<p style="color:red;">This is a red paragraph.</p>
You will learn more about styles in our HTML Styles chapter.

The lang Attribute
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
You can see all the language codes in our HTML Language Code Reference.

The title Attribute
The title attribute defines some extra information about an element.

The value of the title attribute will be displayed as a tooltip when you mouse over the element:

Example
<p title="I'm a tooltip">This is a paragraph.</p>
We Suggest: Always Use Lowercase Attributes
The HTML standard does not require lowercase attribute names.

Single or Double Quotes?
Double quotes around attribute values are the most common in HTML, but single quotes can also be used.

In some situations, when the attribute value itself contains double quotes, it is necessary to use single quotes:

<p title='John "ShotGun" Nelson'>
Or vice versa:

<p title="John 'ShotGun' Nelson">
Chapter Summary
All HTML elements can have attributes
The href attribute of <a> specifies the URL of the page the link goes to
The src attribute of <img> specifies the path to the image to be displayed
The width and height attributes of <img> provide size information for images
The alt attribute of <img> provides an alternate text for an image
The style attribute is used to add styles to an element, such as color, font, size, and more
The lang attribute of the <html> tag declares the language of the Web page
The title attribute defines some extra information about an element

#HTML Headings
HTML headings are titles or subtitles that you want to display on a webpage.

Example
Heading 1
Heading 2
Heading 3
Heading 4
Heading 5
Heading 6
HTML Headings
HTML headings are defined with the <h1> to <h6> tags.

<h1> defines the most important heading. <h6> defines the least important heading.

Example
<h1>Heading 1</h1>
<h2>Heading 2</h2>
<h3>Heading 3</h3>
<h4>Heading 4</h4>
<h5>Heading 5</h5>
<h6>Heading 6</h6>
Note: Browsers automatically add some white space (a margin) before and after a heading.

Headings Are Important
Search engines use the headings to index the structure and content of your web pages.

Users often skim a page by its headings. It is important to use headings to show the document structure.

<h1> headings should be used for main headings, followed by <h2> headings, then the less important <h3>, and so on.

Note: Use HTML headings for headings only. Don't use headings to make text BIG or bold.

Bigger Headings
Each HTML heading has a default size. However, you can specify the size for any heading with the style attribute, using the CSS font-size property:

Example
<h1 style="font-size:60px;">Heading 1</h1>

Tag	Description
<html>	Defines the root of an HTML document
<body>	Defines the document's body
<h1> to <h6>	Defines HTML headings

#HTML Paragraphs
A paragraph always starts on a new line, and is usually a block of text.

HTML Paragraphs
The HTML <p> element defines a paragraph.

A paragraph always starts on a new line, and browsers automatically add some white space (a margin) before and after a paragraph.

#HTML Display
You cannot be sure how HTML will be displayed.

Large or small screens, and resized windows will create different results.

With HTML, you cannot change the display by adding extra spaces or extra lines in your HTML code.

The browser will automatically remove any extra spaces and lines when the page is displayed:

Example
<p>
This paragraph
contains a lot of lines
in the source code,
but the browser
ignores it.
</p>

<p>
This paragraph
contains         a lot of spaces
in the source         code,
but the        browser
ignores it.
</p>

HTML Horizontal Rules
The <hr> tag defines a thematic break in an HTML page, and is most often displayed as a horizontal rule.

The <hr> element is used to separate content (or define a change) in an HTML page:

Example
<h1>This is heading 1</h1>
<p>This is some text.</p>
<hr>
<h2>This is heading 2</h2>
<p>This is some other text.</p>
<hr>

The <hr> tag is an empty tag, which means that it has no end tag.

HTML Line Breaks
The HTML <br> element defines a line break.

Use <br> if you want a line break (a new line) without starting a new paragraph:

Example
<p>This is<br>a paragraph<br>with line breaks.</p>
The <br> tag is an empty tag, which means that it has no end tag.

The Poem Problem
This poem will display on a single line:

Example
<p>
  My Bonnie lies over the ocean.

  My Bonnie lies over the sea.

  My Bonnie lies over the ocean.

  Oh, bring back my Bonnie to me.
</p>
Solution - The HTML <pre> Element
The HTML <pre> element defines preformatted text.

The text inside a <pre> element is displayed in a fixed-width font (usually Courier), and it preserves both spaces and line breaks:

Example
<pre>
  My Bonnie lies over the ocean.

  My Bonnie lies over the sea.

  My Bonnie lies over the ocean.

  Oh, bring back my Bonnie to me.
</pre>

#HTML Tag Reference

Tag	Description
<p>	Defines a paragraph
<hr>	Defines a thematic change in the content
<br>	Inserts a single line break
<pre>	Defines pre-formatted text

#HTML Styles
The HTML style attribute is used to add styles to an element, such as color, font, size, and more.

The HTML Style Attribute
Setting the style of an HTML element, can be done with the style attribute.

The HTML style attribute has the following syntax:

<tagname style="property:value;">
The property is a CSS property. The value is a CSS value.

Background Color
The CSS background-color property defines the background color for an HTML element.

Example
Set the background color for a page to powderblue:

<body style="background-color:powderblue;">

<h1>This is a heading</h1>
<p>This is a paragraph.</p>

</body>

#Text Color
The CSS color property defines the text color for an HTML element:

Example
<h1 style="color:blue;">This is a heading</h1>
<p style="color:red;">This is a paragraph.</p>
Fonts
The CSS font-family property defines the font to be used for an HTML element:

Example
<h1 style="font-family:verdana;">This is a heading</h1>
<p style="font-family:courier;">This is a paragraph.</p>
Text Size
The CSS font-size property defines the text size for an HTML element:

Example
<h1 style="font-size:300%;">This is a heading</h1>
<p style="font-size:160%;">This is a paragraph.</p>
Text Alignment
The CSS text-align property defines the horizontal text alignment for an HTML element:

Example
<h1 style="text-align:center;">Centered Heading</h1>
<p style="text-align:center;">Centered paragraph.</p>
Chapter Summary
Use the style attribute for styling HTML elements
Use background-color for background color
Use color for text colors
Use font-family for text fonts
Use font-size for text sizes
Use text-align for text alignment
