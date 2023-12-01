#HTML Text Formatting
HTML contains several elements for defining text with a special meaning.

Example
This text is bold

This text is italic

This is subscript and superscript

HTML Formatting Elements
Formatting elements were designed to display special types of text:

<b> - Bold text
<strong> - Important text
<i> - Italic text
<em> - Emphasized text
<mark> - Marked text
<small> - Smaller text
<del> - Deleted text
<ins> - Inserted text
<sub> - Subscript text
<sup> - Superscript text
HTML <b> and <strong> Elements
The HTML <b> element defines bold text, without any extra importance.

Example
<b>This text is bold</b>
The HTML <strong> element defines text with strong importance. The content inside is typically displayed in bold.

Example
<strong>This text is important!</strong>

HTML <i> and <em> Elements
The HTML <i> element defines a part of text in an alternate voice or mood. The content inside is typically displayed in italic.

Tip: The <i> tag is often used to indicate a technical term, a phrase from another language, a thought, a ship name, etc.

Example
<i>This text is italic</i>
The HTML <em> element defines emphasized text. The content inside is typically displayed in italic.

Tip: A screen reader will pronounce the words in <em> with an emphasis, using verbal stress.

Example
<em>This text is emphasized</em>
HTML <small> Element
The HTML <small> element defines smaller text:

Example
<small>This is some smaller text.</small>
HTML <mark> Element
The HTML <mark> element defines text that should be marked or highlighted:

Example
<p>Do not forget to buy <mark>milk</mark> today.</p>
HTML <del> Element
The HTML <del> element defines text that has been deleted from a document. Browsers will usually strike a line through deleted text:

Example
<p>My favorite color is <del>blue</del> red.</p>
HTML <ins> Element
The HTML <ins> element defines a text that has been inserted into a document. Browsers will usually underline inserted text:

Example
<p>My favorite color is <del>blue</del> <ins>red</ins>.</p>
HTML <sub> Element
The HTML <sub> element defines subscript text. Subscript text appears half a character below the normal line, and is sometimes rendered in a smaller font. Subscript text can be used for chemical formulas, like H2O:

Example
<p>This is <sub>subscripted</sub> text.</p>
HTML <sup> Element
The HTML <sup> element defines superscript text. Superscript text appears half a character above the normal line, and is sometimes rendered in a smaller font. Superscript text can be used for footnotes, like WWW[1]:

Example
<p>This is <sup>superscripted</sup> text.</p>
#HTML Text Formatting Elements
Tag	Description
<b>	Defines bold text
<em>	Defines emphasized text 
<i>	Defines a part of text in an alternate voice or mood
<small>	Defines smaller text
<strong>	Defines important text
<sub>	Defines subscripted text
<sup>	Defines superscripted text
<ins>	Defines inserted text
<del>	Defines deleted text
<mark>	Defines marked/highlighted text

#HTML Quotation and Citation Elements
In this chapter we will go through the <blockquote>,<q>, <abbr>, <address>, <cite>, and <bdo> HTML elements.

#HTML <blockquote> for Quotations
The HTML <blockquote> element defines a section that is quoted from another source.

Browsers usually indent <blockquote> elements.

Example
<p>Here is a quote from WWF's website:</p>
<blockquote cite="http://www.worldwildlife.org/who/index.html">
For 60 years, WWF has worked to help people and nature thrive. As the world's leading conservation organization, WWF works in nearly 100 countries. At every level, we collaborate with people around the world to develop and deliver innovative solutions that protect communities, wildlife, and the places in which they live.
</blockquote>

#HTML <q> for Short Quotations
The HTML <q> tag defines a short quotation.

Browsers normally insert quotation marks around the quotation.

Example
<p>WWF's goal is to: <q>Build a future where people live in harmony with nature.</q></p> 

HTML <address> for Contact Information
The HTML <address> tag defines the contact information for the author/owner of a document or an article.

The contact information can be an email address, URL, physical address, phone number, social media handle, etc.

The text in the <address> element usually renders in italic, and browsers will always add a line break before and after the <address> element.

Example
<address>
Written by John Doe.<br>
Visit us at:<br>
Example.com<br>
Box 564, Disneyland<br>
USA
</address>
HTML <cite> for Work Title
The HTML <cite> tag defines the title of a creative work (e.g. a book, a poem, a song, a movie, a painting, a sculpture, etc.).

Note: A person's name is not the title of a work.

The text in the <cite> element usually renders in italic.

Example
<p><cite>The Scream</cite> by Edvard Munch. Painted in 1893.</p>
HTML <bdo> for Bi-Directional Override
BDO stands for Bi-Directional Override.

The HTML <bdo> tag is used to override the current text direction:

Example
<bdo dir="rtl">This text will be written from right to left</bdo>

#HTML comments are not displayed in the browser, but they can help document your HTML source code.

HTML Comment Tag
You can add comments to your HTML source by using the following syntax:

<!-- Write your comments here -->
Notice that there is an exclamation point (!) in the start tag, but not in the end tag.

Note: Comments are not displayed by the browser, but they can help document your HTML source code.

Add Comments
With comments you can place notifications and reminders in your HTML code:

Example
<!-- This is a comment -->

<p>This is a paragraph.</p>

<!-- Remember to add more information here -->
Hide Content
Comments can be used to hide content.

This can be helpful if you hide content temporarily:

Example
<p>This is a paragraph.</p>

<!-- <p>This is another paragraph </p> -->

<p>This is a paragraph too.</p>
You can also hide more than one line. Everything between the <!-- and the --> will be hidden from the display.

Example
Hide a section of HTML code:

<p>This is a paragraph.</p>
<!--
<p>Look at this cool image:</p>
<img border="0" src="pic_trulli.jpg" alt="Trulli">
-->
<p>This is a paragraph too.</p>
Comments are also great for debugging HTML, because you can comment out HTML lines of code, one at a time, to search for errors.

#Hide Inline Content
Comments can be used to hide parts in the middle of the HTML code.

Example
Hide a part of a paragraph:

<p>This <!-- great text --> is a paragraph.</p>
#HTML Colors
HTML colors are specified with predefined color names, or with RGB, HEX, HSL, RGBA, or HSLA values.

Color Names
In HTML, a color can be specified by using a color name:

Tomato
Orange
DodgerBlue
MediumSeaGreen
Gray
SlateBlue
Violet
LightGray

HTML supports 140 standard color names.

Background Color
You can set the background color for HTML elements:

Hello World


Lorem ipsum dolor sit amet, consectetuer adipiscing elit, sed diam nonummy nibh euismod tincidunt ut laoreet dolore magna aliquam erat volutpat. Ut wisi enim ad minim veniam, quis nostrud exerci tation ullamcorper suscipit lobortis nisl ut aliquip ex ea commodo consequat.

Example
<h1 style="background-color:DodgerBlue;">Hello World</h1>
<p style="background-color:Tomato;">Lorem ipsum...</p>
Text Color
You can set the color of text:

Hello World
Lorem ipsum dolor sit amet, consectetuer adipiscing elit, sed diam nonummy nibh euismod tincidunt ut laoreet dolore magna aliquam erat volutpat.

Ut wisi enim ad minim veniam, quis nostrud exerci tation ullamcorper suscipit lobortis nisl ut aliquip ex ea commodo consequat.

Example
<h1 style="color:Tomato;">Hello World</h1>
<p style="color:DodgerBlue;">Lorem ipsum...</p>
<p style="color:MediumSeaGreen;">Ut wisi enim...</p>
ADVERTISEMENT

Border Color
You can set the color of borders:

Hello World
Hello World
Hello World
Example
<h1 style="border:2px solid Tomato;">Hello World</h1>
<h1 style="border:2px solid DodgerBlue;">Hello World</h1>
<h1 style="border:2px solid Violet;">Hello World</h1>
Color Values
In HTML, colors can also be specified using RGB values, HEX values, HSL values, RGBA values, and HSLA values.

The following three <div> elements have their background color set with RGB, HEX, and HSL values:

rgb(255, 99, 71)
#ff6347
hsl(9, 100%, 64%)
The following two <div> elements have their background color set with RGBA and HSLA values, which add an Alpha channel to the color (here we have 50% transparency):

rgba(255, 99, 71, 0.5)
hsla(9, 100%, 64%, 0.5)
Example
<h1 style="background-color:rgb(255, 99, 71);">...</h1>
<h1 style="background-color:#ff6347;">...</h1>
<h1 style="background-color:hsl(9, 100%, 64%);">...</h1>

<h1 style="background-color:rgba(255, 99, 71, 0.5);">...</h1>
<h1 style="background-color:hsla(9, 100%, 64%, 0.5);">...</h1>


