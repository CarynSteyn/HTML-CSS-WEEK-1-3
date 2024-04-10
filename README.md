HTML & CSS 

HTML-Hyper Text Markup Language 
HTML is the standard markup language used for creating webpages , it describes the structure of a webpage . HTML consist of a series of elements . these elements tell the browser how to display the content.
for example : The h1 element defines a large heading , while the p element defines a paragraph.
WHAT IS A HTML ELEMENT ?
An HTML element is defined by a start tag {opening tag} ,some content and an end tag {closing tag}.
h1 CONTENT h1
The HTML element is everything from the start tag to the end tag.

HTML Syntax - 
this is a language that is used to structure web pages - uses tags 

DOM - Document Object Model
this becomes important when working with CSS or JAVASCRIPT  

THE BROWSER USES DOM to CREATE AN ACCESSIBILITY TREE ....

h1 - serves as the main heading   /  h6 - serves as the least important heading
h2 - acts as a subtitle for the content 

There are four HTML elements - two for BOLD and two for ITALICS 

e.g. I - ITALICS   B - BOLD

q - stands for quote 

HTML supports 140 standard color names.
IN HTML colors are specified using predefined color names.


DATE ELEMENT -

e.g. <time datetime="2025-05-8"> May 8 </time>


TIME ELEMENTS 

<time datetime="14:15:28.5"> 14:15:28.5 </time> 

 HTML simplifies this by using a single element called <time>


GLOBAL ATTRIBUTES 

When looking at global attributes in HTML that work universally, we will focus on four highly useful ones. The class attribute is the most commonly used. It allows us to assign a reusable name to any element, which can then be styled using CSS for all elements sharing that class. 

NB.HTML even has a significant impact on human rights.



HTML Links.
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
ADVERTISEMENT

HTML Links - Use an Image as a Link
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
Tip: Learn more about JavaScript in our JavaScript Tutorial.

Link Titles
The title attribute specifies extra information about an element. The information is most often shown as a tooltip text when the mouse moves over the element.

Example
<a href="https://www.w3schools.com/html/" title="Go to W3Schools HTML section">Visit our HTML Tutorial</a>
More on Absolute URLs and Relative URLs
Example
Use a full URL to link to a web page: 

<a href="https://www.w3schools.com/html/default.asp">HTML tutorial</a>

Example
Link to a page located in the html folder on the current web site: 

<a href="/html/default.asp">HTML tutorial</a>

Example
Link to a page located in the same folder as the current page: 

<a href="default.asp">HTML tutorial</a>

You can read more about file paths in the chapter HTML File Paths.

Chapter Summary
Use the <a> element to define a link
Use the href attribute to define the link address
Use the target attribute to define where to open the linked document
Use the <img> element (inside <a>) to use an image as a link
Use the mailto: scheme inside the href attribute to create a link that opens the user's email program
HTML Link Tags
Tag	Description
<a>	Defines a hyperlink.

HTML ATTRIBUTES 
HTML attributes provide additional information about HTML elements.
All HTML elements can have attributes .Attributes are always specified in the start tag .

1. SRC-ATTRIBUTE = The image URL is placed into the source .
2. ALT-ATTRIBUTE = This serves as a replacement for the image when it can not be seen.
3. WIDTH&HEIGHT-ATTRIBUTES= This will determine the size of the image.  e.g. {pixels}.
4. Href-ATTRIBUTE= This allows you to create a hyper link.

CSS
CSS-CASCADING STYLE SHEETS 
CSS describes how HTML elements are to be displayed on screen ,paper or on any other media.
CSS saves allot of work and it can control the layout of multiple webpages all at once.

IMAGES 
When you want to add a image to a webpage - WE USE THE IMAGE ELEMENT - IMG - <img src="" alt="">



