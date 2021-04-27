# HtmlTut
What is Doctype?
====================================================================================
Doctype: A doctype or document type declaration is an instruction that tells the web browser about the markup language in which the current page is written. The Doctype is not an element or tag, it lets the browser know about the version of or standard of HTML or any other markup language that is being used in the document.

Declaration of a Doctype: A DOCTYPE declaration appears at the top of a web page before all other elements. According to the HTML specification or standards, every HTML document requires a document type declaration to ensure that the pages are displayed in the way they are intended to be displayed.

The DOCTYPE for HTML5 is case-insensitive and can be written as shown below:

< !DOCTYPE html >
Doctype Usage: In the version, HTML 4.01, the usage of DOCTYPE declaration was to create a reference to a document type definition (DTD), since the version HTML 4.01 was completely based on a Standard Generalized Markup Language(SGML).
The document type definition (DTD) is responsible for specifying the rules for the Standard Generalized Markup Language(SGML) so that the browser processes the content correctly. But in the HTML version, HTML 5 there isn’t any need for a reference to a document type definition (DTD) because HTML 5 is not based on a Standard Generalized Markup Language(SGML).

In HTML 5, the DOCTYPE declaration is only required for enabling the standard mode for writing documents.
The <!DOCTYPE html> declaration defines that this document is an HTML5 document
The <html> element is the root element of an HTML page
The <head> element contains meta information about the HTML page
The <title> element specifies a title for the HTML page (which is shown in the browser's title bar or in the page's tab)
The <body> element defines the document's body, and is a container for all the visible contents, such as headings, paragraphs, images, hyperlinks, tables, lists, etc.
The <h1> element defines a large heading
The <p> element defines a paragraph
all heading tags <h1>---<h6> and paragraph tags <p> are block level elements 
HTML links are defined with the <a> tag:
HTML images are defined with the <img> tag.
The source file (src), alternative text (alt), width, and height are provided as attributes:
img attributes src,alt,width,height
<a>,<img> are inline elements
<hr> is block level element
The <hr> tag is an empty tag, which means that it has no end tag.
<br> is line break 
The <br> tag is an empty tag, which means that it has no end tag.
There are two ways to specify the URL in the src attribute:

1. Absolute URL - Links to an external image that is hosted on another website. Example: src="https://www.w3schools.com/images/img_girl.jpg".

Notes: External images might be under copyright. If you do not get permission to use it, you may be in violation of copyright laws. In addition, you cannot control external images; it can suddenly be removed or changed.

2. Relative URL - Links to an image that is hosted within the website. Here, the URL does not include the domain name. If the URL begins without a slash, it will be relative to the current page. Example: src="img_girl.jpg". If the URL begins with a slash, it will be relative to the domain. Example: src="/images/img_girl.jpg".

Tip: It is almost always best to use relative URLs. They will not break if you change domain.
--------------------------------------------------------------------------------------
HTML - The Head Element
------------------------
The HTML <head> element is a container for the following elements: <title>, <style>, <meta>, <link>, <script>, and <base>.
The HTML <link> Element
The <link> element defines the relationship between the current document and an external resource.
The <link> tag is most often used to link to external style sheets:
<link rel="stylesheet" href="mystyle.css">
The HTML <meta> Element
The <meta> element is typically used to specify the character set, page description, keywords, author of the document, and viewport settings.
The metadata will not be displayed on the page, but are used by browsers (how to display content or reload page), by search engines (keywords), and other web services.
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
----------------------------------------------------------------------
The HTML <base> Element
The <base> element specifies the base URL and/or target for all relative URLs in a page.
The <base> tag must have either an href or a target attribute present, or both.
There can only be one single <base> element in a document!
<head>
<base href="https://www.w3schools.com/" target="_blank">
</head>
<body>
<img src="images/stickman.gif" width="24" height="39" alt="Stickman">
<a href="tags/tag_base.asp">HTML base Tag</a>
</body>
----------------------------------------------------------------------------------
The style Attribute
---------------------
The style attribute is used to add styles to an element, such as color, font, size, and more.
The lang Attribute
---------------------------
<html lang="en">
You should always include the lang attribute inside the <html> tag, to declare the language of the Web page. This is meant to assist search engines and browsers.
Country codes can also be added to the language code in the lang attribute. So, the first two characters define the language of the HTML page, and the last two characters define the country.
<html lang="en-US">
----------------------------------------------------------------------------
The title Attribute
-------------------------
The title attribute defines some extra information about an element.
The value of the title attribute will be displayed as a tooltip when you mouse over the element:
<p title="I'm a tooltip">This is a paragraph.</p>

Single or Double Quotes?
-------------------------
Double quotes around attribute values are the most common in HTML, but single quotes can also be used.
In some situations, when the attribute value itself contains double quotes, it is necessary to use single quotes:
<p title='John "ShotGun" Nelson'>
<p title="John 'ShotGun' Nelson">
--------------------------------------------------------------------------
Headings Are Important
-----------------------
Search engines use the headings to index the structure and content of your web pages.
Users often skim a page by its headings. It is important to use headings to show the document structure.
<h1> headings should be used for main headings, followed by <h2> headings, then the less important <h3>, and so on.
Note: Use HTML headings for headings only. Don't use headings to make text BIG or bold.
Bigger Headings
Each HTML heading has a default size. However, you can specify the size for any heading with the style attribute, using the CSS font-size property:
<h1 style="font-size:60px;">Heading 1</h1>
------------------------------------------------------------------------
The HTML <pre> Element
The HTML <pre> element defines preformatted text.
The text inside a <pre> element is displayed in a fixed-width font (usually Courier), and it preserves both spaces and line breaks:
-------------------------------------------------------------------------
HTML Formatting Elements
Formatting elements were designed to display special types of text:

<b> - Bold text =>The HTML <b> element defines bold text, without any extra importance.
<strong> - Important text => <strong> element defines text with strong importance. The content inside is typically displayed in bold
<i> - Italic text => <i> element defines a part of text in an alternate voice or mood. The content inside is typically displayed in italic.
Tip: The <i> tag is often used to indicate a technical term, a phrase from another language, a thought, a ship name, etc.
<em> - Emphasized text => The HTML <em> element defines emphasized text. The content inside is typically displayed in italic.
Tip: A screen reader will pronounce the words in <em> with an emphasis, using verbal stress.
<mark> - Marked text => The HTML <mark> element defines text that should be marked or highlighted:
<small> - Smaller text => <small> element defines smaller text:
<del> - Deleted text => The HTML <del> element defines text that has been deleted from a document. Browsers will usually strike a line through deleted text:
<ins> - Inserted text => The HTML <ins> element defines a text that has been inserted into a document. Browsers will usually underline inserted text:
<p>My favorite color is <del>blue</del> <ins>red</ins>.</p>
<sub> - Subscript text => The HTML <sub> element defines subscript text. Subscript text appears half a character below the normal line, and is sometimes rendered in a smaller font. Subscript text can be used for chemical formulas, like H2O:
<sup> - Superscript text => The HTML <sup> element defines superscript text. Superscript text appears half a character above the normal line, and is sometimes rendered in a smaller font. Superscript text can be used for footnotes, like WWW[1]:
the above elements have inline elements
----------------------------------------------------------------------------
HTML Comment Tags
--------------------
<!-- Write your comments here -->
Note: Comments are not displayed by the browser, but they can help document your HTML source code.
-----------------------------------------------------------------------------------
HTML Links - The target Attribute
----------------------------------
By default, the linked page will be displayed in the current browser window. To change this, you must specify another target for the link.
The target attribute specifies where to open the linked document.
The target attribute can have one of the following values:
_self - Default. Opens the document in the same window/tab as it was clicked
_blank - Opens the document in a new window or tab
_parent - Opens the document in the parent frame
_top - Opens the document in the full body of the window
-------------------------------------------------------------------------------
<picture>
  <source srcset="img_avatar.png">
  <source srcset="img_girl.jpg">
  <img src="img_beatles.gif" alt="Beatles" style="width:auto;">
</picture>
-----------------------------------------------------------------------------
<th colspan="2">Telephone</th>
<th rowspan="2">Telephone:</th>
---------------------------------------------------------------------------
HTML Layout Elements
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
----------------------------------------------------------------------------------------

