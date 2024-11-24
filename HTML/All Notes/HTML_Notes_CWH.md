# Introduction

- HTML : Hyper Text Markup Language
- HTML is the language of the web. It is used to create websites
- We use HTML tags to define look & feel of a website.
- With understanding of these tags and how to put them together, we can create beautiful websites easily.

## Then Why CSS and JavaScript

- HTML is used for defining layout of a page : A barebone page structure.
- CSS is used to add styling to that barebone page created using HTML.
- JavaScript is used ot program logic for the page layout eg. what happens when a user hover on a text, when to hide or show elements etc.

## Analogy

- HTML :- Car body (only metal)
- CSS :- Car paint, decoration etc.
- JavaScript :- Car engine + interior logic

# Chapter 1 : Creating our first Website

- We start building a website by creating a file named index.html.
- index.html is a special filename which is presented when the website root address is typed.

## A Basic HTML Page

<!DOCTYPE html>
<html lang="en"> 
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>My Website</title>/> 
  </head>
  <body> 
    <h1>This is a heading </h1> 
    <p>My paragraph</p>
  </body> 
</html>

- A tag is like a container for either content or other HTML tags.

## Imp notes

- Head & body tags are children of HTML tag.
- HTML is the parent of head & body tags
- Most of the HTML elements have opening & closing tag with content in between opening & closing tags.
- Some HTML tags have no content. These are called Empty Elements eg. <br>
- We can wither use .htm or .html extension
- We can use "Inspect Element" or "View Page Source" option from chrome to look into a website's HTML code.

HTML element = start tag + content + End tag

## Comments in in HTML

- Comments in HTMl are used to mark text which should not be parsed. They can help document the source code.

  <!-- HTML Comment -->

## Case Sensitivity

- HTML is a case insensitive langaue. <H1> and <h1> tags are the same.

# Chapter 2 : Basic HTML Tags

- We can add elements inside the body tag to define the page layout.

## HTML Element

- Everything from starting to the ending tag.
  <body>  :- opening tag
  content
  </body> :- closing tag

## HTML Attributes

- used to add more information corresponding to an HTML tag.
- Example : <a href="https://google.com/">Google </a>
  - <a> :- anchor tag
  - href="" :- href attribute
- We can either use single or double quotes in attributes

## Heading tag

- Heading tag is usec to mark headings in HTML.
- From h1 to h6, we have tags for the most important to the least important heading.

  <h1>Most Important heading</h1>
  <h2>Another heading h2</h2>
  <h3>Another heading h3</h3>
  <h4>Another heading h4</h4>
  <h5>Another heading h5</h5>
  <h6>Another heading h6</h6>

- Note : We should not use HTML headings to make text thick or bold.

## The Parapgraph tag

- Paragraph tags are used to add paragraphs to an HTML page.
  <p> This is a paragraph </p>

## The Anchor tag

- The Anchor tag is used to add links to an existing content inside an HTML page.
  <a href="htps://google.com">Click me </a>

## The img tag

- img tag is used to add images in an HTML page
  <img src="image.jpg"> : retrive url of an image

## Bold, italic and underline tags

- We can use bold, italic and underline tags to highlight the text as follows:
  <b> This is bold </b>
  <i> This is italic </i>
  <u> This is underline </u>

## br tag

- The br tag is used to create line breaks in an HTML document

## big and small tags

- We can make the text a bit larger and a bit smaller using big and small tags respectively.

## hr tag

- <hr> tag in HTML is used to create a horizontal ruler often used to separate the content.

## Subscript & superscript

- We can add subscript and superscript in HTML as follows:
  <sub> This </sub> is subscript
  <sup> This </sup> is superscript

## pre tag

- HTML always ignores extra spaces and newline. In order to display a piece of text as is, we use pre tag.
  <pre>
      This is written
      using pre
      tag
  </pre>

# Chapter 3 : Creating a page layout

- When we use the right tag in right place, it results in a better page layout, better indexing by search engines and better user experience.
- We use the following tag to get the job done.

  <header>
  <main>
  <footer>

- Header tag contains nav tag
- Inside the main tag we insert the following tags:
  <main>    :- The main opening tag
  <section> :- A page section
  <article> :- a sekf contained content
  <aside>   :- content aside from the content (eg. ads etc.)
  </main>   :- The main closing tag

- Creating a page like this is not necessary but it created a readable & structured layout.
- Also they are useful for SEO (Search Engine Optimization).

## Link Attributes

- <a href="/conact"> Contact us </a> :- Contact page open in same tab
- <a href="/contact" target="blank">Contact us </a> :- Opens in a new tab
- We can put any content inside an anchor tag (images, headings etc are all allowed).
- If the page is inside a directory, we need to make sure that we link to the correct page. (same applies to img tag as well)
- We can add links to images like this
  <a href="/about"><img src="a.jpg" width="120"> </a> :- Height will be set automatically.

## The div tag

- div tag is often used as a container for other elements div is a block level element.
- It always takes full width.

## The span tag

- span is an inline container
- Takes as much width as necessary

# Chapter 4 : Lists, Tables and forms

## Lists

- Lists are used to display content which represents a list.

### unordered list

- Used to list unordered items.
  <ul>
    <li> Home </li>
    <li> About </li>
        .......
        .......
        .......
  </ul>

### ordered list

- Used to list ordered items.
  <ol>
    <li> Phone </li>
    <li> PC </li>
    <li> Laptop </li>
  </ol>

## Tables

- The <table> tag is used to define in HTML.
- It is used to format & display tabular data.
- <tr> tag  : used to display table row
- <td> tag  : used to display table data
- <th> tag  : used to place of table data for displaying table header
- We can define as many table rows as we want.
- To add a caption to the table, we use <caption> tag inside table.
- <thead> tag : used to wrap table head (caption & tr with th)
- <tbody> tag : used to wrap the table body.
- colspan="" attribute : This attribute is used to create cells spanning multiple columns.
  <th colspan="3">Jayesh </th>  
   - Spans 3 columns
- rowspan="" attribute : This attribute is used to create cells spanning multiple rows.
  <th rowspan="3">Jayesh</th>
  - spans 3 rows

## HTML Forms

- An HTML form is used to collect input from the user form tag is used for the same.
  <form>
  ---Element of the form---
  </form>
- There are different form elements for different kinds of user input.

### input element:

- Can be of type text, checkbox, radio, button and submit.
- We can also have a 'file' type.

### textarea element:

- Defines a multiline text input.
- Cols and rows attributes can be used to size the textarea.

### select element:

- Defines a drop down list

- note : you don't have to remember all the tags, you will automatically memorize them with practice.

### Embedding videos

- Video tag is used to play videos in HTML
  <video src="video.mp4">Error</video>

### Attributes for video

- We can use :
  - width : to adjust width of a video (Height automatically adjusts)
  - We can use autoplay/loop to autoplay or loop the video.

# Chapter 5 : Search Engine Optimization (SEO)

- We will focus only on HTML standpoint of SEO. We will not be looking into keyword building and content optimization aspect of SEO.

## Types of SEO

1. On page SEO : can be done by HTML developers
2. Off page SEO

## HTML SEO

- HTML developers can implement SEO using the following techniques:

- Set the title very nice & to the point
- Set the meta description
  - <meta name="description" content="...">
- Set a nice URL slug.
- Set the meta keywords tag.
- Set the meta author tag.
  - <meta name="author" content="Jayesh">
- Set a favicon
- Compress images & other resources
- Remove unused HTML/CSS & Js files + compress them
- Add alt text to images
