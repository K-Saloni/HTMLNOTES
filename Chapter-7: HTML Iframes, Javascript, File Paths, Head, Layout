#HTML Iframes
An HTML iframe is used to display a web page within a web page.

HTML Iframe Syntax
The HTML <iframe> tag specifies an inline frame.

An inline frame is used to embed another document within the current HTML document.

Syntax
<iframe src="url" title="description"></iframe>
Tip: It is a good practice to always include a title attribute for the <iframe>. This is used by screen readers to read out what the content of the iframe is.

Iframe - Set Height and Width
Use the height and width attributes to specify the size of the iframe.

The height and width are specified in pixels by default:

Example
<iframe src="demo_iframe.htm" height="200" width="300" title="Iframe Example"></iframe>
Or you can add the style attribute and use the CSS height and width properties:

Example
<iframe src="demo_iframe.htm" style="height:200px;width:300px;" title="Iframe Example"></iframe>

#Iframe - Remove the Border
By default, an iframe has a border around it.

To remove the border, add the style attribute and use the CSS border property:

Example
<iframe src="demo_iframe.htm" style="border:none;" title="Iframe Example"></iframe>
With CSS, you can also change the size, style and color of the iframe's border:

Example
<iframe src="demo_iframe.htm" style="border:2px solid red;" title="Iframe Example"></iframe>
Iframe - Target for a Link
An iframe can be used as the target frame for a link.

The target attribute of the link must refer to the name attribute of the iframe:

Example
<iframe src="demo_iframe.htm" name="iframe_a" title="Iframe Example"></iframe>


Chapter Summary
The HTML <iframe> tag specifies an inline frame
The src attribute defines the URL of the page to embed
Always include a title attribute (for screen readers)
The height and width attributes specify the size of the iframe
Use border:none; to remove the border around the iframe

#HTML iframe Tag
Tag	Description
<iframe>	Defines an inline frame

#HTML JavaScript
JavaScript makes HTML pages more dynamic and interactive.

Example
My First JavaScript
Click me to display Date and Time

<!DOCTYPE html>
<html>
<body>

<h1>My First JavaScript</h1>

<button type="button"
onclick="document.getElementById('demo').innerHTML = Date()">
Click me to display Date and Time.</button>

<p id="demo"></p>

</body>
</html> 

#The HTML <script> Tag
The HTML <script> tag is used to define a client-side script (JavaScript).

The <script> element either contains script statements, or it points to an external script file through the src attribute.

Common uses for JavaScript are image manipulation, form validation, and dynamic changes of content.

To select an HTML element, JavaScript most often uses the document.getElementById() method.

This JavaScript example writes "Hello JavaScript!" into an HTML element with id="demo": 

<!DOCTYPE html>
<html>
<body>

<h2>Use JavaScript to Change Text</h2>
<p>This example writes "Hello JavaScript!" into an HTML element with id="demo":</p>

<p id="demo"></p>

<script>
document.getElementById("demo").innerHTML = "Hello JavaScript!";
</script> 

</body>
</html> 

#A Taste of JavaScript
Here are some examples of what JavaScript can do:
<!DOCTYPE html>
<html>
<body>

<h1>My First JavaScript</h1>

<p>JavaScript can change the content of an HTML element:</p>

<button type="button" onclick="myFunction()">Click Me!</button>

<p id="demo">This is a demonstration.</p>

<script>
function myFunction() { 
  document.getElementById("demo").innerHTML = "Hello JavaScript!";
}
</script>

</body>
</html>

<!DOCTYPE html>
<html>
<body>

<h1>My First JavaScript</h1>

<p id="demo">JavaScript can change the style of an HTML element.</p>

<script>
function myFunction() {
  document.getElementById("demo").style.fontSize = "25px"; 
  document.getElementById("demo").style.color = "red";
  document.getElementById("demo").style.backgroundColor = "yellow";        
}
</script>

<button type="button" onclick="myFunction()">Click Me!</button>

</body>
</html>


<!DOCTYPE html>
<html>
<body>

<h1>My First JavaScript</h1>
<p>Here, a JavaScript changes the value of the src (source) attribute of an image.</p>

<script>
function light(sw) {
  var pic;
  if (sw == 0) {
    pic = "pic_bulboff.gif"
  } else {
    pic = "pic_bulbon.gif"
  }
  document.getElementById('myImage').src = pic;
}
</script>

<img id="myImage" src="pic_bulboff.gif" width="100" height="180">

<p>
<button type="button" onclick="light(1)">Light On</button>
<button type="button" onclick="light(0)">Light Off</button>
</p>

</body>
</html>

#HTML Script Tags
Tag	Description
<script>	Defines a client-side script
<noscript>	Defines an alternate content for users that do not support client-side scripts

#HTML File Paths
A file path describes the location of a file in a web site's folder structure.

File Path Examples
Path	Description
<img src="picture.jpg">	The "picture.jpg" file is located in the same folder as the current page
<img src="images/picture.jpg">	The "picture.jpg" file is located in the images folder in the current folder
<img src="/images/picture.jpg">	The "picture.jpg" file is located in the images folder at the root of the current web
<img src="../picture.jpg">	The "picture.jpg" file is located in the folder one level up from the current folder
HTML File Paths
A file path describes the location of a file in a web site's folder structure.

File paths are used when linking to external files, like:

Web pages
Images
Style sheets
JavaScripts


HTML - The Head Element
The HTML <head> element is a container for the following elements: <title>, <style>, <meta>, <link>, <script>, and <base>.

The HTML <head> Element
The <head> element is a container for metadata (data about data) and is placed between the <html> tag and the <body> tag.

HTML metadata is data about the HTML document. Metadata is not displayed.

Metadata typically define the document title, character set, styles, scripts, and other meta information.

The HTML <title> Element
The <title> element defines the title of the document. The title must be text-only, and it is shown in the browser's title bar or in the page's tab.

The <title> element is required in HTML documents!

The content of a page title is very important for search engine optimization (SEO)! The page title is used by search engine algorithms to decide the order when listing pages in search results.

The <title> element:

defines a title in the browser toolbar
provides a title for the page when it is added to favorites
displays a title for the page in search engine-results
So, try to make the title as accurate and meaningful as possible!

A simple HTML document:

Example
<!DOCTYPE html>
<html>
<head>
  <title>A Meaningful Page Title</title>
</head>
<body>

The content of the document......

</body>
</html>
The HTML <style> Element
The <style> element is used to define style information for a single HTML page:

Example
<style>
  body {background-color: powderblue;}
  h1 {color: red;}
  p {color: blue;}
</style>

#The HTML <link> Element
The <link> element defines the relationship between the current document and an external resource.

The <link> tag is most often used to link to external style sheets:

Example
<link rel="stylesheet" href="mystyle.css">

#The HTML <meta> Element
The <meta> element is typically used to specify the character set, page description, keywords, author of the document, and viewport settings.

The metadata will not be displayed on the page, but is used by browsers (how to display content or reload page), by search engines (keywords), and other web services.

Examples
Define the character set used:

<meta charset="UTF-8">
Define keywords for search engines:

<meta name="keywords" content="HTML, CSS, JavaScript">
Define a description of your web page:

<meta name="description" content="Free Web tutorials">
Define the author of a page:

<meta name="author" content="John Doe">
Refresh document every 30 seconds:

<meta http-equiv="refresh" content="30">
Setting the viewport to make your website look good on all devices:

<meta name="viewport" content="width=device-width, initial-scale=1.0">
Example of <meta> tags:

Example
<meta charset="UTF-8">
<meta name="description" content="Free Web tutorials">
<meta name="keywords" content="HTML, CSS, JavaScript">
<meta name="author" content="John Doe">
Setting The Viewport
The viewport is the user's visible area of a web page. It varies with the device - it will be smaller on a mobile phone than on a computer screen.

You should include the following <meta> element in all your web pages:

<meta name="viewport" content="width=device-width, initial-scale=1.0">
This gives the browser instructions on how to control the page's dimensions and scaling.

The width=device-width part sets the width of the page to follow the screen-width of the device (which will vary depending on the device).

The initial-scale=1.0 part sets the initial zoom level when the page is first loaded by the browser.

Here is an example of a web page without the viewport meta tag, and the same web page with the viewport meta tag:

Tip: If you are browsing this page with a phone or a tablet, you can click on the two links below to see the difference.


#The HTML <script> Element
The <script> element is used to define client-side JavaScripts.

The following JavaScript writes "Hello JavaScript!" into an HTML element with id="demo":

Example
<script>
function myFunction() {
  document.getElementById("demo").innerHTML = "Hello JavaScript!";
}
</script>

#The HTML <base> Element
The <base> element specifies the base URL and/or target for all relative URLs in a page.

The <base> tag must have either an href or a target attribute present, or both.

There can only be one single <base> element in a document!

Example
Specify a default URL and a default target for all links on a page:

<head>
<base href="https://www.w3schools.com/" target="_blank">
</head>

<body>
<img src="images/stickman.gif" width="24" height="39" alt="Stickman">
<a href="tags/tag_base.asp">HTML base Tag</a>
</body>

#Chapter Summary
The <head> element is a container for metadata (data about data)
The <head> element is placed between the <html> tag and the <body> tag
The <title> element is required and it defines the title of the document
The <style> element is used to define style information for a single document
The <link> tag is most often used to link to external style sheets
The <meta> element is typically used to specify the character set, page description, keywords, author of the document, and viewport settings
The <script> element is used to define client-side JavaScripts
The <base> element specifies the base URL and/or target for all relative URLs in a page
HTML head Elements
Tag	Description
<head>	Defines information about the document
<title>	Defines the title of a document
<base>	Defines a default address or a default target for all links on a page
<link>	Defines the relationship between a document and an external resource
<meta>	Defines metadata about an HTML document
<script>	Defines a client-side script
<style>	Defines style information for a document

#HTML Layout Elements and Techniques
Websites often display content in multiple columns (like a magazine or a newspaper).

#HTML Layout Elements
HTML has several semantic elements that define the different parts of a web page:

HTML5 Semantic Elements	
<header> - Defines a header for a document or a section
<nav> - Defines a set of navigation links
<section> - Defines a section in a document
<article> - Defines an independent, self-contained content
<aside> - Defines content aside from the content (like a sidebar)
<footer> - Defines a footer for a document or a section
<details> - Defines additional details that the user can open and close on demand
<summary> - Defines a heading for the <details> element
You can read more about semantic elements in our HTML Semantics chapter.

HTML Layout Techniques
There are four different techniques to create multicolumn layouts. Each technique has its pros and cons:

CSS framework
CSS float property
CSS flexbox
CSS grid


