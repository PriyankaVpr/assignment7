1)HTML (HyperText Markup Language) is the standard language used for creating web pages. 

2)why - to put contents

3)Emmet is a plugin for many text editors that allows for fast coding of HTML and CSS. It uses abbreviations that expand into full-fledged HTML and CSS code snippets.(html:5,ul>li*5,div#header,a,table>tr*3>td*2)

4)<!DOCTYPE html>
<html>
<head>
    <title>Page Title</title>
</head>
<body>
    <h1>This is a Heading</h1>
    <p>This is a paragraph.</p>
</body>
</html>

5)The <head> tag contains meta-information about the HTML document. It includes elements such as:
<title>,<script>

6)The <body> tag contains the actual content of the web page that is visible to users. This includes:
Text
Images
Links
Tables
Forms

7)Three important HTML elements are:

<h1> to <h6>: Heading tags, used to define headings.
<p>: Paragraph tag, used to define paragraphs.
<a>: Anchor tag, used to create hyperlinks.


8)Tags: Tags are the syntax used to define elements. They are written within angle brackets, like <tagname>.
Elements: Elements consist of the opening tag, content, and closing tag. For example, <p>This is a paragraph.</p> is a paragraph element where <p> is the opening tag, This is a paragraph. is the content, and </p> is the closing tag. Some elements, like <img>, are self-closing and do not have content or a closing tag.

CSS


1)CSS (Cascading Style Sheets) is a stylesheet language used to describe the presentation of a document written in HTML

2)CSS is used to:
Separate content from design, making it easier to maintain and update web pages.
Improve the look and feel of web pages.

3)<link rel="stylesheet" href="styles.css">
Emmet Shortcut: link:css

4)FONT 
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Roboto">

COLOR
body {
  color: #333;
  background-color: #f0f0f0;
}

IMAGE
<img src="path/to/image.jpg" alt="Description">


5)Text Family
font-family: 'Roboto', sans-serif;
font-size: 16px;
font-weight: bold;
line-height: 1.5;
text-align: center;
text-decoration: underline;


Color & Background Family:
color: #333;
background-color: #f0f0f0;
background-image: url('background.jpg');
background-repeat: no-repeat;
background-size: cover;


Box Model:
margin: 10px;
padding: 20px;
border: 1px solid #ccc;
width: 200px;
height: 150px;


6)Background Image: Use for decorative purposes or when the image is part of the design, not content.
body {
  background-image: url('background.jpg');
}


Image Tag: Use when the image is part of the content and should be visible in the document flow.
<img src="image.jpg" alt="Description">


7)Layout: The arrangement of elements on a webpage.
Flexbox Properties: Flexbox is a layout model that allows elements to align and distribute space within a container.
display: flex;
flex-direction;
justify-content;

8)Tailwind CSS is a utility-first CSS framework that provides low-level utility classes to build custom designs without leaving HTML. It is used because:

It allows for rapid prototyping.
It provides a consistent design system.



