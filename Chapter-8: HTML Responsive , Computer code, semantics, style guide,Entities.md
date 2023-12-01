#HTML Responsive Web Design
Responsive web design is about creating web pages that look good on all devices!

A responsive web design will automatically adjust for different screen sizes and viewports.

What is Responsive Web Design?
Responsive Web Design is about using HTML and CSS to automatically resize, hide, shrink, or enlarge, a website, to make it look good on all devices (desktops, tablets, and phones):


Setting The Viewport
To create a responsive website, add the following <meta> tag to all your web pages:

Example
<meta name="viewport" content="width=device-width, initial-scale=1.0">
This will set the viewport of your page, which will give the browser instructions on how to control the page's dimensions and scaling.

#Responsive Images
Responsive images are images that scale nicely to fit any browser size.

#Responsive Web Design - Frameworks
All popular CSS Frameworks offer responsive design.

They are free, and easy to use.

#Bootstrap
Another popular CSS framework is Bootstrap:

Example
<!DOCTYPE html>
<html lang="en">
<head>
<title>Bootstrap 5 Example</title>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.3/dist/css/bootstrap.min.css" rel="stylesheet">
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.2.3/dist/js/bootstrap.bundle.min.js"></script>
</head>
<body>

<div class="container-fluid p-5 bg-primary text-white text-center">
  <h1>My First Bootstrap Page</h1>
  <p>Resize this responsive page to see the effect!</p>
</div>

<div class="container mt-5">
  <div class="row">
    <div class="col-sm-4">
      <h3>Column 1</h3>
      <p>Lorem ipsum...</p>
    </div>
    <div class="col-sm-4">
      <h3>Column 2</h3>
      <p>Lorem ipsum...</p>
    </div>
    <div class="col-sm-4">
      <h3>Column 3</h3>
      <p>Lorem ipsum...</p>
    </div>
  </div>
</div>

#HTML Computer Code Elements
HTML contains several elements for defining user input and computer code.

Example
<code>
x = 5;
y = 6;
z = x + y;
</code>

#HTML <kbd> For Keyboard Input
The HTML <kbd> element is used to define keyboard input. The content inside is displayed in the browser's default monospace font.

Example
Define some text as keyboard input in a document:

<p>Save the document by pressing <kbd>Ctrl + S</kbd></p>
Result:

Save the document by pressing Ctrl + S
HTML <samp> For Program Output
The HTML <samp> element is used to define sample output from a computer program. The content inside is displayed in the browser's default monospace font.

Example
Define some text as sample output from a computer program in a document:

<p>Message from my computer:</p>
<p><samp>File not found.<br>Press F1 to continue</samp></p>
Result:

Message from my computer:
File not found.
Press F1 to continue

#HTML <code> For Computer Code
The HTML <code> element  is used to define a piece of computer code. The content inside is displayed in the browser's default monospace font.

Example
Define some text as computer code in a document:

<code>
x = 5;
y = 6;
z = x + y;
</code>
Result:

x = 5; y = 6; z = x + y;
Notice that the <code> element does not preserve extra whitespace and line-breaks.

To fix this, you can put the <code> element inside a <pre> element:

Example
<pre>
<code>
x = 5;
y = 6;
z = x + y;
</code>
</pre>
Result:

x = 5;
y = 6;
z = x + y;
HTML <var> For Variables
The HTML <var> element  is used to define a variable in programming or in a mathematical expression. The content inside is typically displayed in italic.

Example
Define some text as variables in a document:

<p>The area of a triangle is: 1/2 x <var>b</var> x <var>h</var>, where <var>b</var> is the base, and <var>h</var> is the vertical height.</p>
Result:

The area of a triangle is: 1/2 x b x h, where b is the base, and h is the vertical height.
Chapter Summary
The <kbd> element defines keyboard input
The <samp> element defines sample output from a computer program
The <code> element defines a piece of computer code
The <var> element defines a variable in programming or in a mathematical expression
The <pre> element defines preformatted text

#HTML Computer Code Elements
Tag	Description
<code>	Defines programming code
<kbd>	Defines keyboard input 
<samp>	Defines computer output
<var>	Defines a variable
<pre>	Defines preformatted text

#HTML Semantic Elements
Semantic elements = elements with a meaning.

What are Semantic Elements?
A semantic element clearly describes its meaning to both the browser and the developer.

Examples of non-semantic elements: <div> and <span> - Tells nothing about its content.

Examples of semantic elements: <form>, <table>, and <article> - Clearly defines its content.

Semantic Elements in HTML
Many web sites contain HTML code like: <div id="nav"> <div class="header"> <div id="footer"> to indicate navigation, header, and footer.

In HTML there are some semantic elements that can be used to define different parts of a web page:  

<article>
<aside>
<details>
<figcaption>
<figure>
<footer>
<header>
<main>
<mark>
<nav>
<section>
<summary>
<time>
HTML Semantic Elements
HTML <section> Element
The <section> element defines a section in a document.

According to W3C's HTML documentation: "A section is a thematic grouping of content, typically with a heading."

Examples of where a <section> element can be used:

Chapters
Introduction
News items
Contact information
A web page could normally be split into sections for introduction, content, and contact information.

Example
Two sections in a document:

<section>
<h1>WWF</h1>
<p>The World Wide Fund for Nature (WWF) is an international organization working on issues regarding the conservation, research and restoration of the environment, formerly named the World Wildlife Fund. WWF was founded in 1961.</p>
</section>

<section>
<h1>WWF's Panda symbol</h1>
<p>The Panda has become the symbol of WWF. The well-known panda logo of WWF originated from a panda named Chi Chi that was transferred from the Beijing Zoo to the London Zoo in the same year of the establishment of WWF.</p>
</section>

#HTML <article> Element
The <article> element specifies independent, self-contained content.

An article should make sense on its own, and it should be possible to distribute it independently from the rest of the web site.

Examples of where the <article> element can be used:

Forum posts
Blog posts
User comments
Product cards
Newspaper articles
Example
Three articles with independent, self-contained content:

<article>
<h2>Google Chrome</h2>
<p>Google Chrome is a web browser developed by Google, released in 2008. Chrome is the world's most popular web browser today!</p>
</article>

<article>
<h2>Mozilla Firefox</h2>
<p>Mozilla Firefox is an open-source web browser developed by Mozilla. Firefox has been the second most popular web browser since January, 2018.</p>
</article>

<article>
<h2>Microsoft Edge</h2>
<p>Microsoft Edge is a web browser developed by Microsoft, released in 2015. Microsoft Edge replaced Internet Explorer.</p>
</article>
Example 2
Use CSS to style the <article> element:

<html>
<head>
<style>
.all-browsers {
  margin: 0;
  padding: 5px;
  background-color: lightgray;
}

.all-browsers > h1, .browser {
  margin: 10px;
  padding: 5px;
}

.browser {
  background: white;
}

.browser > h2, p {
  margin: 4px;
  font-size: 90%;
}
</style>
</head>
<body>

<article class="all-browsers">
  <h1>Most Popular Browsers</h1>
  <article class="browser">
    <h2>Google Chrome</h2>
    <p>Google Chrome is a web browser developed by Google, released in 2008. Chrome is the world's most popular web browser today!</p>
  </article>
  <article class="browser">
    <h2>Mozilla Firefox</h2>
    <p>Mozilla Firefox is an open-source web browser developed by Mozilla. Firefox has been the second most popular web browser since January, 2018.</p>
  </article>
  <article class="browser">
    <h2>Microsoft Edge</h2>
    <p>Microsoft Edge is a web browser developed by Microsoft, released in 2015. Microsoft Edge replaced Internet Explorer.</p>
  </article>
</article>

</body>
</html>
Nesting <article> in <section> or Vice Versa?
The <article> element specifies independent, self-contained content.

The <section> element defines section in a document.

Can we use the definitions to decide how to nest those elements? No, we cannot!

So, you will find HTML pages with <section> elements containing <article> elements, and <article> elements containing <section> elements.

HTML <header> Element
The <header> element represents a container for introductory content or a set of navigational links.

A <header> element typically contains:

one or more heading elements (<h1> - <h6>)
logo or icon
authorship information
Note: You can have several <header> elements in one HTML document. However, <header> cannot be placed within a <footer>, <address> or another <header> element.

Example
A header for an <article>: 

<article>
  <header>
    <h1>What Does WWF Do?</h1>
    <p>WWF's mission:</p>
  </header>
  <p>WWF's mission is to stop the degradation of our planet's natural environment,
  and build a future in which humans live in harmony with nature.</p>
</article>
HTML <footer> Element
The <footer> element defines a footer for a document or section.

A <footer> element typically contains:

authorship information
copyright information
contact information
sitemap
back to top links
related documents
You can have several <footer> elements in one document.

Example
A footer section in a document:

<footer>
  <p>Author: Hege Refsnes</p>
  <p><a href="mailto:hege@example.com">hege@example.com</a></p>
</footer>
HTML <nav> Element
The <nav> element defines a set of navigation links.

Notice that NOT all links of a document should be inside a <nav> element. The <nav> element is intended only for major blocks of navigation links.

Browsers, such as screen readers for disabled users, can use this element to determine whether to omit the initial rendering of this content.

Example
A set of navigation links:

<nav>
  <a href="/html/">HTML</a> |
  <a href="/css/">CSS</a> |
  <a href="/js/">JavaScript</a> |
  <a href="/jquery/">jQuery</a>
</nav>
HTML <aside> Element
The <aside> element defines some content aside from the content it is placed in (like a sidebar).

The <aside> content should be indirectly related to the surrounding content.

Example
Display some content aside from the content it is placed in:

<p>My family and I visited The Epcot center this summer. The weather was nice, and Epcot was amazing! I had a great summer together with my family!</p>

<aside>
<h4>Epcot Center</h4>
<p>Epcot is a theme park at Walt Disney World Resort featuring exciting attractions, international pavilions, award-winning fireworks and seasonal special events.</p>
</aside>
Example 2
Use CSS to style the <aside> element:

<html>
<head>
<style>
aside {
  width: 30%;
  padding-left: 15px;
  margin-left: 15px;
  float: right;
  font-style: italic;
  background-color: lightgray;
}
</style>
</head>
<body>

<p>My family and I visited The Epcot center this summer. The weather was nice, and Epcot was amazing! I had a great summer together with my family!</p>

<aside>
<p>The Epcot center is a theme park at Walt Disney World Resort featuring exciting attractions, international pavilions, award-winning fireworks and seasonal special events.</p>
</aside>

<p>My family and I visited The Epcot center this summer. The weather was nice, and Epcot was amazing! I had a great summer together with my family!</p>
<p>My family and I visited The Epcot center this summer. The weather was nice, and Epcot was amazing! I had a great summer together with my family!</p>

</body>
</html>
HTML <figure> and <figcaption> Elements
The <figure> tag specifies self-contained content, like illustrations, diagrams, photos, code listings, etc.

The <figcaption> tag defines a caption for a <figure> element. The <figcaption> element can be placed as the first or as the last child of a <figure> element.

The <img> element defines the actual image/illustration. 

Example
<figure>
  <img src="pic_trulli.jpg" alt="Trulli">
  <figcaption>Fig1. - Trulli, Puglia, Italy.</figcaption>
</figure>

#Semantic Elements in HTML
Below is a list of some of the semantic elements in HTML.

Tag	Description
<article>	Defines independent, self-contained content
<aside>	Defines content aside from the page content
<details>	Defines additional details that the user can view or hide
<figcaption>	Defines a caption for a <figure> element
<figure>	Specifies self-contained content, like illustrations, diagrams, photos, code listings, etc.
<footer>	Defines a footer for a document or section
<header>	Specifies a header for a document or section
<main>	Specifies the main content of a document
<mark>	Defines marked/highlighted text
<nav>	Defines navigation links
<section>	Defines a section in a document
<summary>	Defines a visible heading for a <details> element
<time>	Defines a date/time

#HTML Style Guide
A consistent, clean, and tidy HTML code makes it easier for others to read and understand your code.

Here are some guidelines and tips for creating good HTML code.

Always Declare Document Type
Always declare the document type as the first line in your document.

The correct document type for HTML is:

<!DOCTYPE html>
Use Lowercase Element Names
HTML allows mixing uppercase and lowercase letters in element names.

However, we recommend using lowercase element names, because:

Mixing uppercase and lowercase names looks bad
Developers normally use lowercase names
Lowercase looks cleaner
Lowercase is easier to write
Good:
<body>
<p>This is a paragraph.</p>
</body>
Bad:
<BODY>
<P>This is a paragraph.</P>
</BODY> 

#Close All HTML Elements
In HTML, you do not have to close all elements (for example the <p> element).

However, we strongly recommend closing all HTML elements, like this:

Good:
<section>
  <p>This is a paragraph.</p>
  <p>This is a paragraph.</p>
</section>
Bad:
<section>
  <p>This is a paragraph.
  <p>This is a paragraph.
</section>
Use Lowercase Attribute Names
HTML allows mixing uppercase and lowercase letters in attribute names.

However, we recommend using lowercase attribute names, because:

Mixing uppercase and lowercase names looks bad
Developers normally use lowercase names
Lowercase looks cleaner
Lowercase is easier to write
Good:
<a href="https://www.w3schools.com/html/">Visit our HTML tutorial</a>
Bad:
<a HREF="https://www.w3schools.com/html/">Visit our HTML tutorial</a>
Always Quote Attribute Values
HTML allows attribute values without quotes.

However, we recommend quoting attribute values, because:

Developers normally quote attribute values
Quoted values are easier to read
You MUST use quotes if the value contains spaces
Good:
<table class="striped">
Bad:
<table class=striped>
Very bad:
This will not work, because the value contains spaces:

<table class=table striped>
Always Specify alt, width, and height for Images
Always specify the alt attribute for images. This attribute is important if the image for some reason cannot be displayed.

Also, always define the width and height of images. This reduces flickering, because the browser can reserve space for the image before loading.

Good:
<img src="html5.gif" alt="HTML5" style="width:128px;height:128px">
Bad:
<img src="html5.gif">
Spaces and Equal Signs
HTML allows spaces around equal signs. But space-less is easier to read and groups entities better together.

Good:
<link rel="stylesheet" href="styles.css">
Bad:
<link rel = "stylesheet" href = "styles.css">
Avoid Long Code Lines
When using an HTML editor, it is NOT convenient to scroll right and left to read the HTML code.

Try to avoid too long code lines.

Blank Lines and Indentation
Do not add blank lines, spaces, or indentations without a reason.

For readability, add blank lines to separate large or logical code blocks.

For readability, add two spaces of indentation. Do not use the tab key.

Good:
<body>

<h1>Famous Cities</h1>

<h2>Tokyo</h2>
<p>Tokyo is the capital of Japan, the center of the Greater Tokyo Area, and the most populous metropolitan area in the world.</p>

<h2>London</h2>
<p>London is the capital city of England. It is the most populous city in the United Kingdom.</p>

<h2>Paris</h2>
<p>Paris is the capital of France. The Paris area is one of the largest population centers in Europe.</p>

</body>
Bad:
<body>
<h1>Famous Cities</h1>
<h2>Tokyo</h2><p>Tokyo is the capital of Japan, the center of the Greater Tokyo Area, and the most populous metropolitan area in the world.</p>
<h2>London</h2><p>London is the capital city of England. It is the most populous city in the United Kingdom.</p>
<h2>Paris</h2><p>Paris is the capital of France. The Paris area is one of the largest population centers in Europe.</p>
</body>
Good Table Example:
<table>
  <tr>
    <th>Name</th>
    <th>Description</th>
  </tr>
  <tr>
    <td>A</td>
    <td>Description of A</td>
  </tr>
  <tr>
    <td>B</td>
    <td>Description of B</td>
  </tr>
</table>
Good List Example:
<ul>
  <li>London</li>
  <li>Paris</li>
  <li>Tokyo</li>
</ul>
Never Skip the <title> Element
The <title> element is required in HTML.

The contents of a page title is very important for search engine optimization (SEO)! The page title is used by search engine algorithms to decide the order when listing pages in search results.

The <title> element:

defines a title in the browser toolbar
provides a title for the page when it is added to favorites
displays a title for the page in search-engine results
So, try to make the title as accurate and meaningful as possible: 

<title>HTML Style Guide and Coding Conventions</title>
Omitting <html> and <body>?
An HTML page will validate without the <html> and <body> tags:

Example
<!DOCTYPE html>
<head>
  <title>Page Title</title>
</head>

<h1>This is a heading</h1>
<p>This is a paragraph.</p>
However, we strongly recommend to always add the <html> and <body> tags!

Omitting <body> can produce errors in older browsers.

Omitting <html> and <body> can also crash DOM and XML software.

Omitting <head>?
The HTML <head> tag can also be omitted.

Browsers will add all elements before <body>, to a default <head> element.

Example
<!DOCTYPE html>
<html>
<title>Page Title</title>
<body>

<h1>This is a heading</h1>
<p>This is a paragraph.</p>

</body>
</html>
However, we recommend using the <head> tag.

Close Empty HTML Elements?
In HTML, it is optional to close empty elements.

Allowed:
<meta charset="utf-8">
Also Allowed:
<meta charset="utf-8" />
If you expect XML/XHTML software to access your page, keep the closing slash (/), because it is required in XML and XHTML.

Add the lang Attribute
You should always include the lang attribute inside the <html> tag, to declare the language of the Web page. This is meant to assist search engines and browsers.

Example
<!DOCTYPE html>
<html lang="en-us">
<head>
  <title>Page Title</title>
</head>
<body>

<h1>This is a heading</h1>
<p>This is a paragraph.</p>

</body>
</html>
Meta Data
To ensure proper interpretation and correct search engine indexing, both the language and the character encoding <meta charset="charset"> should be defined as early as possible in an HTML document:

<!DOCTYPE html>
<html lang="en-us">
<head>
  <meta charset="UTF-8">
  <title>Page Title</title>
</head>
Setting The Viewport
The viewport is the user's visible area of a web page. It varies with the device - it will be smaller on a mobile phone than on a computer screen.

You should include the following <meta> element in all your web pages:

<meta name="viewport" content="width=device-width, initial-scale=1.0">
This gives the browser instructions on how to control the page's dimensions and scaling.

The width=device-width part sets the width of the page to follow the screen-width of the device (which will vary depending on the device).

The initial-scale=1.0 part sets the initial zoom level when the page is first loaded by the browser.

#HTML Comments
Short comments should be written on one line, like this:

<!-- This is a comment -->
Comments that spans more than one line, should be written like this:

<!--
  This is a long comment example. This is a long comment example.
  This is a long comment example. This is a long comment example.
-->
Long comments are easier to observe if they are indented with two spaces.

Using Style Sheets
Use simple syntax for linking to style sheets (the type attribute is not necessary):

<link rel="stylesheet" href="styles.css">
Short CSS rules can be written compressed, like this:

p.intro {font-family:Verdana;font-size:16em;}
Long CSS rules should be written over multiple lines:

body {
  background-color: lightgrey;
  font-family: "Arial Black", Helvetica, sans-serif;
  font-size: 16em;
  color: black;
}
Place the opening bracket on the same line as the selector
Use one space before the opening bracket
Use two spaces of indentation
Use semicolon after each property-value pair, including the last
Only use quotes around values if the value contains spaces
Place the closing bracket on a new line, without leading spaces
Loading JavaScript in HTML
Use simple syntax for loading external scripts (the type attribute is not necessary):

<script src="myscript.js">
Accessing HTML Elements with JavaScript
Using "untidy" HTML code can result in JavaScript errors.

These two JavaScript statements will produce different results:

Example
getElementById("Demo").innerHTML = "Hello";

getElementById("demo").innerHTML = "Hello";

#Use Lower Case File Names
Some web servers (Apache, Unix) are case sensitive about file names: "london.jpg" cannot be accessed as "London.jpg".

Other web servers (Microsoft, IIS) are not case sensitive: "london.jpg" can be accessed as "London.jpg".

If you use a mix of uppercase and lowercase, you have to be aware of this.

If you move from a case-insensitive to a case-sensitive server, even small errors will break your web!

To avoid these problems, always use lowercase file names!

File Extensions
HTML files should have a .html extension (.htm is allowed).

CSS files should have a .css extension.

JavaScript files should have a .js extension.

Differences Between .htm and .html?
There is no difference between the .htm and .html file extensions!

Both will be treated as HTML by any web browser and web server.

Default Filenames
When a URL does not specify a filename at the end (like "https://www.w3schools.com/"), the server just adds a default filename, such as "index.html", "index.htm", "default.html", or "default.htm".

If your server is configured only with "index.html" as the default filename, your file must be named "index.html", and not "default.html".

However, servers can be configured with more than one default filename; usually you can set up as many default filenames as you want.

#HTML Entities
Reserved characters in HTML must be replaced with entities:

< (less than) = &lt;
> (greather than) = &gt;
HTML Character Entities
Some characters are reserved in HTML.

If you use the less than (<) or greater than (>) signs in your HTML text, the browser might mix them with tags.

Entity names or entity numbers can be used to display reserved HTML characters.

Entity names look like this:

&entity_name;
Entity numbers look like this:

&#entity_number;
To display a less than sign (<) we must write: &lt; or &#60;

Entity names are easier to remember than entity numbers.

Non-breaking Space
A commonly used HTML entity is the non-breaking space: &nbsp;

A non-breaking space is a space that will not break into a new line.

Two words separated by a non-breaking space will stick together (not break into a new line). This is handy when breaking the words might be disruptive.

Examples:

§ 10
10 km/h
10 PM
Another common use of the non-breaking space is to prevent browsers from truncating spaces in HTML pages.

If you write 10 spaces in your text, the browser will remove 9 of them. To add real spaces to your text, you can use the &nbsp; character entity.

The non-breaking hyphen (&#8209;) is used to define a hyphen character (‑) that does not break into a new line.

#Some Useful HTML Character Entities
Result	Description	Name	Number	
non-breaking space	&nbsp;	&#160;	
<	less than	&lt;	&#60;	
>	greater than	&gt;	&#62;	
&	ampersand	&amp;	&#38;	
"	double quotation mark	&quot;	&#34;	
'	single quotation mark	&apos;	&#39;	
¢	cent	&cent;	&#162;	
£	pound	&pound;	&#163;	
¥	yen	&yen;	&#165;	
€	euro	&euro;	&#8364;	
©	copyright	&copy;	&#169;	
®	trademark	&reg;	&#174;	
Note
Entity names are case sensitive.

Combining Diacritical Marks
A diacritical mark is a "glyph" added to a letter.

Some diacritical marks, like grave (  ̀) and acute (  ́) are called accents.

Diacritical marks can be used in combination with alphanumeric characters to produce a character that is not present in the character set (encoding) used in the page.

Here are some examples:

Mark	Character	Construct	Result	
 ̀	a	a&#768;	à	
 ́	a	a&#769;	á	
̂	a	a&#770;	â	
 ̃	a	a&#771;	ã	
 ̀	O	O&#768;	Ò	
 ́	O	O&#769;	Ó	
̂	O	O&#770;	Ô	
 ̃	O	O&#771;	Õ	
