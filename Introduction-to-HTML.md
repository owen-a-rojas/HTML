# What's HTML?

***HTML, or HyperText Markup Language,*** is the standard markup language used to create and design documents on the World Wide Web. It's the basic building block of web development and is essential for creating the structure of web pages. HTML provides a way to structure content, such as headings, paragraphs, lists, links, images, and other elements.

## What's HTML used for?

+ ***Creating Web Pages:*** HTML is the foundational language for building web pages. It allows you to define the structure of a webpage by organizing content into various elements like headings, paragraphs, lists, images, links, and more.

+ ***Hyperlinking:*** HTML enables the creation of hyperlinks, which are clickable elements that allow users to navigate between different web pages. Links are created using the ```<a>``` (anchor) element.

+ ***Document Structure:*** HTML provides a hierarchical structure to web documents, using elements like ```<head>``` for metadata, ```<body>``` for the main content, and various other elements for headings, paragraphs, and lists.

+ ***Semantic Markup:*** HTML includes semantic elements that convey meaning about the content. For example, ```<header>,``` ```<nav>,``` ```<article>,``` ```<section>,``` ```<footer>,``` etc., provide semantic information about the purpose of different parts of the webpage.

+ ***Forms:*** HTML includes form elements (such as ```<form>,``` ```<input>,``` ```<select>,``` ```<textarea>```) that allow users to input data. Forms are often used for user interactions, like submitting data or conducting searches.

+ ***Multimedia Integration:*** HTML supports embedding multimedia elements such as images ```(<img>),``` audio ```(<audio>),``` and video ```(<video>).```

+ ***Accessibility:*** HTML includes features that contribute to web accessibility, such as alternative text for images ```(alt attribute),``` which is important for users with visual impairments using screen readers.

+ ***Compatibility with CSS and JavaScript:*** HTML is often used in conjunction with CSS ```(Cascading Style Sheets)``` for styling and layout, and JavaScript for adding interactivity and dynamic behavior to web pages.

+ ***Responsive Web Design:*** HTML, along with CSS, is crucial for creating responsive web designs that adapt to different screen sizes and devices.


## Structure of a HTML Document

<img src="https://www.codewithfaraz.com/img/learn%20html%20basics%20introduction%20to%20html%20structure%20and%20elements.png" width="300px" />

## What are HTML Tags

 They are used to define and structure the content of a web page. Tags are enclosed in angle brackets < > and typically come in pairs opening tags and closing tags. The closing tag has a forward slash before the tag name.

 + ***Document Structure:***

```<html>:``` Root element of an HTML document.
```<head>:``` Contains metadata about the document.
```<title>:``` Sets the title of the document.
```<body>:``` Contains the main content of the document.

+ ***Text Formatting:***

```<h1>, <h2>, <h3>, <h4>, <h5>, <h6>:``` Heading tags (1 being the largest and 6 the smallest).
```<p>:``` Paragraph.
```<strong>``` or ```<b>:``` Bold text.
```<em>``` or ```<i>:``` Italicized text.
```<u>:``` Underlined text.


+ ***Lists:***

```<ul>:``` Unordered list.
```<ol>:``` Ordered list.
```<li>:``` List item.

+ ***Links and Images:***

```<a>:``` Anchor tag for creating hyperlinks.
```<img>:``` Image tag for embedding images.

+ ***Tables:***

```<table>:``` Defines a table.
```<tr>:``` Defines a table row.
```<th>:``` Defines a table header cell.
```<td>:``` Defines a table data cell.

+ ***Forms:***

```<form>:``` Defines an HTML form.
```<input>:``` Input field within a form.
```<select>:``` Dropdown list.
```<textarea>:``` Multiline text input.
```<button>:``` Defines a clickable button.

+ ***Semantic Elements:***

```<header>, <nav>, <main>, <article>, <section>, <aside>, <footer>:``` 

Provide semantic meaning to different parts of the document.

+ ***Comments:***

```<!-- Comment goes here -->:``` 

Used for adding comments within the HTML code.

## What’s a HTML element?

An HTML element is a fundamental building block of an HTML document. It consists of a start tag, some content, and an end tag (in most cases). The combination of the start tag, content, and end tag forms a complete HTML element. HTML elements are used to structure and define the content on a web page. 

```<start_tag>Content</end_tag>```

+ ***Start Tag*** ```(<start_tag>):``` This is the opening part of the HTML element. It is enclosed in angle brackets and indicates the beginning of the element. The tag name specifies the type of element.

+ ***Content:*** This is the actual content of the element. It could be text, other elements, or a combination of both.

+ ***End Tag*** ```(</end_tag>):``` This is the closing part of the HTML element. It is also enclosed in angle brackets and includes a forward slash before the tag name. The end tag signifies the end of the element.

***Here's an example using the ```<p>``` (paragraph) element:***

```<p>This is a paragraph.</p>```

***In this example:***

```<p>``` is the start tag.

This is a paragraph. is the content.

```</p>``` is the end tag.

HTML elements can be nested inside each other, allowing for the creation of complex document structures. Additionally, some elements are self-closing and don't have a separate end tag. These are typically used for elements that don't contain content or have attributes.

***For example,*** the ```<img>``` (image) element is self-closing:

```<img src="example.jpg" alt="An example image">```

In this case, there is no separate end tag for ```<img>.``` The information about the image is provided using attributes within the start tag.


## What’s a HTML empty element?

An HTML empty element, also known as a self closing or void element, is an HTML element that does not have any content between an opening tag and a closing tag. Instead, it may include attributes within the opening tag. These elements are self-contained and do not require a corresponding closing tag.

***Here are some common HTML empty elements:***

+ ```<img>``` (Image):

```<img src="example.jpg" alt="An example image">```

+ ```<br>``` (Line Break):

```<p>```This is a line of text.```<br>```

This is a new line of text.```</p>```

+ ```<hr>``` (Horizontal Rule):

```<p>Some content above the horizontal rule.</p>```
```<hr>```
```<p>Some content below the horizontal rule.</p>```

+ ```<input>``` (Input):

```<input type="text" name="username" placeholder="Enter your username">```

+ ```<meta>``` (Metadata):

```<meta charset="UTF-8">```

## What are HTML attributes?

HTML attributes provide additional information about HTML elements. They are always included in the opening tag of an HTML element and are written as name/value pairs. The attribute name is followed by an equal sign (=), and the attribute value is enclosed in double or single quotation marks. Attributes enhance the functionality or appearance of HTML elements and are crucial for styling, scripting, and providing additional information about elements.

```<tagname attribute_name="attribute_value">Content</tagname>```

***Here are a few examples of common HTML attributes:***

+ ***class:*** Assigns one or more class names to an element for styling purposes.

```<p class="important">This paragraph is important.</p>```

+ ***id:*** Specifies a unique identifier for an element.

```<div id="header">This is the header</div>```

+ ***src:*** Defines the source URL for elements like images or scripts.

```<img src="example.jpg" alt="An example image">```

+ ***href:*** Specifies the URL of a linked resource, commonly used in ```<a>``` (anchor) elements.

```<a href="https://www.example.com">Visit Example.com</a>```

+ ***alt:*** Provides alternative text for elements like images (used for accessibility).

```<img src="example.jpg" alt="An alternative description">```

+ ***width and height:*** Sets the width and height of elements like images.

```<img src="example.jpg" alt="Image" width="300" height="200">```

+ ***style:*** Applies inline CSS styles to an element.

```<p style="color: blue; font-size: 16px;">This paragraph is styled.</p>```

+ ***placeholder:*** Provides a short hint describing the expected value of an input field.

```<input type="text" placeholder="Enter your name">```

## What are HTML global attributes?

HTML global attributes are attributes that can be used with any HTML element, regardless of its type. These attributes provide common functionalities and characteristics that are applicable to a wide range of HTML elements. Global attributes simplify the process of applying consistent features across different elements.

+ ***class:*** Specifies one or more class names for an element, enabling the application of styles through CSS.

```<div class="container">Content goes here</div>```

+ ***id:*** Defines a unique identifier for an element.

<```p id="important-paragraph">This is an important paragraph.</p>```

+ ***style:*** Applies inline CSS styles to an element.

```<p style="color: red; font-size: 18px;">Styled paragraph</p>```

+ ***title:*** Provides additional information about an element, often displayed as a tooltip.

```<a href="https://www.example.com" title="Visit Example.com">Link</a>```

+ ***lang:*** Specifies the language of the content within an element.

```<html lang="en">```
```<!-- ... -->```
```</html>```

+ ***dir:*** Specifies the direction of the text within an element (ltr for left-to-right, rtl for right-to-left).

```<p dir="rtl">This text is right-to-left.</p>```

+ ***data-*:*** Allows custom data attributes to be added to HTML elements. These attributes are often used for JavaScript interactions.

```<div data-toggle="modal" data-target="#myModal">Click me</div>```

+ ***contenteditable:*** Specifies whether the content of an element is editable by the user.

```<div contenteditable="true">Editable content</div>```



























