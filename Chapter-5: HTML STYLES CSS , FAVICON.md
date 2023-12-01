#HTML Page Title
Every web page should have a page title to describe the meaning of the page.

The <title> element adds a title to your page:

Example
<!DOCTYPE html>
<html>
<head>
  <title>HTML Tutorial</title>
</head>
<body>

The content of the document......

</body>
</html>
The title is shown in the browser's title bar:


The title should describe the content and the meaning of the page.

The page title is very important for search engine optimization (SEO). The text is used by search engine algorithms to decide the order when listing pages in search results.

The <title> element:

defines a title in the browser toolbar

#HTML Images
Images can improve the design and the appearance of a web page.

Example
<img src="pic_trulli.jpg" alt="Italian Trulli">
Example
<img src="img_girl.jpg" alt="Girl in a jacket">
Example
<img src="img_chania.jpg" alt="Flowers in Chania">
HTML Images Syntax
The HTML <img> tag is used to embed an image in a web page.

Images are not technically inserted into a web page; images are linked to web pages. The <img> tag creates a holding space for the referenced image.

The <img> tag is empty, it contains attributes only, and does not have a closing tag.

The <img> tag has two required attributes:

src - Specifies the path to the image
alt - Specifies an alternate text for the image
Syntax
<img src="url" alt="alternatetext">
The src Attribute
The required src attribute specifies the path (URL) to the image.

Note: When a web page loads, it is the browser, at that moment, that gets the image from a web server and inserts it into the page. Therefore, make sure that the image actually stays in the same spot in relation to the web page, otherwise your visitors will get a broken link icon. The broken link icon and the alt text are shown if the browser cannot find the image.

Example
<img src="img_chania.jpg" alt="Flowers in Chania">
The alt Attribute
The required alt attribute provides an alternate text for an image, if the user for some reason cannot view it (because of slow connection, an error in the src attribute, or if the user uses a screen reader).

The value of the alt attribute should describe the image:

Example
<img src="img_chania.jpg" alt="Flowers in Chania">
If a browser cannot find an image, it will display the value of the alt attribute:

Example
<img src="wrongname.gif" alt="Flowers in Chania">
Tip: A screen reader is a software program that reads the HTML code, and allows the user to "listen" to the content. Screen readers are useful for people who are visually impaired or learning disabled.

Image Size - Width and Height
You can use the style attribute to specify the width and height of an image.

Example
<img src="img_girl.jpg" alt="Girl in a jacket" style="width:500px;height:600px;">
Alternatively, you can use the width and height attributes:

Example
<img src="img_girl.jpg" alt="Girl in a jacket" width="500" height="600">
The width and height attributes always define the width and height of the image in pixels.

Note: Always specify the width and height of an image. If width and height are not specified, the web page might flicker while the image loads.

Width and Height, or Style?
The width, height, and style attributes are all valid in HTML.

However, we suggest using the style attribute. It prevents styles sheets from changing the size of images:

Example
<!DOCTYPE html>
<html>
<head>
<style>
img {
  width: 100%;
}
</style>
</head>
<body>

<img src="html5.gif" alt="HTML5 Icon" width="128" height="128">

<img src="html5.gif" alt="HTML5 Icon" style="width:128px;height:128px;">

</body>
</html>
Images in Another Folder
If you have your images in a sub-folder, you must include the folder name in the src attribute:

Example
<img src="/images/html5.gif" alt="HTML5 Icon" style="width:128px;height:128px;">
Images on Another Server/Website
Some web sites point to an image on another server.

To point to an image on another server, you must specify an absolute (full) URL in the src attribute:

Notes on external images: External images might be under copyright. If you do not get permission to use it, you may be in violation of copyright laws. In addition, you cannot control external images; they can suddenly be removed or changed.

Animated Images
HTML allows animated GIFs:

Example
<img src="programming.gif" alt="Computer Man" style="width:48px;height:48px;">
Image as a Link
To use an image as a link, put the <img> tag inside the <a> tag:

Example
<a href="default.asp">
  <img src="smiley.gif" alt="HTML tutorial" style="width:42px;height:42px;">
</a>
Image Floating
Use the CSS float property to let the image float to the right or to the left of a text:

Example
<p><img src="smiley.gif" alt="Smiley face" style="float:right;width:42px;height:42px;">
The image will float to the right of the text.</p>

<p><img src="smiley.gif" alt="Smiley face" style="float:left;width:42px;height:42px;">
The image will float to the left of the text.</p>
Tip: To learn more about CSS Float, read our CSS Float Tutorial.

Common Image Formats
Here are the most common image file types, which are supported in all browsers (Chrome, Edge, Firefox, Safari, Opera):

Abbreviation	File Format	File Extension
APNG	Animated Portable Network Graphics	.apng
GIF	Graphics Interchange Format	.gif
ICO	Microsoft Icon	.ico, .cur
JPEG	Joint Photographic Expert Group image	.jpg, .jpeg, .jfif, .pjpeg, .pjp
PNG	Portable Network Graphics	.png
SVG	Scalable Vector Graphics	.svg

Chapter Summary
Use the HTML <img> element to define an image
Use the HTML src attribute to define the URL of the image
Use the HTML alt attribute to define an alternate text for an image, if it cannot be displayed
Use the HTML width and height attributes or the CSS width and height properties to define the size of the image
Use the CSS float property to let the image float to the left or to the right
Note: Loading large images takes time, and can slow down your web page. Use images carefully.

#HTML Links
Links are found in nearly all web pages. Links allow users to click their way from page to page.

HTML Links - Hyperlinks
HTML links are hyperlinks.

You can click on a link and jump to another document.

When you move the mouse over a link, the mouse arrow will turn into a little hand.

Note: A link does not have to be text. A link can be an image or any other HTML element!

HTML Links - Syntax
The HTML <a> tag defines a hyperlink. It has the following syntax:

<a href="url">link text</a>
The most important attribute of the <a> element is the href attribute, which indicates the link's destination.

The link text is the part that will be visible to the reader.

Clicking on the link text, will send the reader to the specified URL address.

Example
This example shows how to create a link to W3Schools.com:

<a href="https://www.w3schools.com/">Visit W3Schools.com!</a>
By default, links will appear as follows in all browsers:

An unvisited link is underlined and blue
A visited link is underlined and purple
An active link is underlined and red
Tip: Links can of course be styled with CSS, to get another look!

HTML Links - The target Attribute
By default, the linked page will be displayed in the current browser window. To change this, you must specify another target for the link.

The target attribute specifies where to open the linked document.

The target attribute can have one of the following values:

_self - Default. Opens the document in the same window/tab as it was clicked
_blank - Opens the document in a new window or tab
_parent - Opens the document in the parent frame
_top - Opens the document in the full body of the window
Example
Use target="_blank" to open the linked document in a new browser window or tab:

<a href="https://www.w3schools.com/" target="_blank">Visit W3Schools!</a>
Absolute URLs vs. Relative URLs
Both examples above are using an absolute URL (a full web address) in the href attribute.

A local link (a link to a page within the same website) is specified with a relative URL (without the "https://www" part):

Example
<h2>Absolute URLs</h2>
<p><a href="https://www.w3.org/">W3C</a></p>
<p><a href="https://www.google.com/">Google</a></p>

<h2>Relative URLs</h2>
<p><a href="html_images.asp">HTML Images</a></p>
<p><a href="/css/default.asp">CSS Tutorial</a></p>

#HTML Links - Use an Image as a Link
To use an image as a link, just put the <img> tag inside the <a> tag:

Example
<a href="default.asp">
<img src="smiley.gif" alt="HTML tutorial" style="width:42px;height:42px;">
</a>
Link to an Email Address
Use mailto: inside the href attribute to create a link that opens the user's email program (to let them send a new email):

Example
<a href="mailto:someone@example.com">Send email</a>
Button as a Link
To use an HTML button as a link, you have to add some JavaScript code.

JavaScript allows you to specify what happens at certain events, such as a click of a button:

Example
<button onclick="document.location='default.asp'">HTML Tutorial</button>

#Link Titles
The title attribute specifies extra information about an element. The information is most often shown as a tooltip text when the mouse moves over the element.


#More on Absolute URLs and Relative URLs
Example
Use a full URL to link to a web page: 

<a href="https://www.w3schools.com/html/default.asp">HTML tutorial</a>

Example
Link to a page located in the html folder on the current web site: 

<a href="/html/default.asp">HTML tutorial</a>

Example
Link to a page located in the same folder as the current page: 

<a href="default.asp">HTML tutorial</a>

#Chapter Summary
Use the <a> element to define a link
Use the href attribute to define the link address
Use the target attribute to define where to open the linked document
Use the <img> element (inside <a>) to use an image as a link
Use the mailto: scheme inside the href attribute to create a link that opens the user's email program
HTML Link Tags
Tag	Description
<a>	Defines a hyperlink
provides a title for the page when it is added to favorites
displays a title for the page in search engine-results
So, try to make the title as accurate and meaningful as possible!

HTML Title Tag
Tag	Description
<title>	Defines the title of the document
