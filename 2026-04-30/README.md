# HTML
- HTML is termed as Hyper Text Markup Language.
- HTML is used for creating web pages.
- HTML is a markup language which is being used for creating the structure of a webpage.

```<!DOCTYPE html>``` is used at the top of the HTML document to notify the browser that existing webpage is a HTML5 document.

```<html lang="en">``` is used to start the HTML document, lang attribute is used to inform that content of the webpage is in English  
```</html>``` is used to notify that HTML document has been ended. All content of the webpage is written between them. HTML document has two seperate element for different purposes.

- ```<head></head>``` is used to provide information or to link other files for the browser and search engine.

- ```<body></body>``` is used to create webpage structure which is visible to the user.

- ```<meta charset="UTF-8">``` is used for defining character encoding to the browser.

- ```<meta name="viewport" content="width=device-width, initial-scale=1.0">``` is used for making website responsive.

- ```<title>Document</title>``` used for providing title to a HTML document.

## HTML Elements

It is defined by a start tag, some content, and an end tag. 

```<tagname> Content </tagname>```

HTML elements can be nested(this means that element can have other elements)

**Note** : Never miss the end tag otherwise it will distort the structure of the webpage.
HTML tags are not case-sensitive.

## Attributes

Attributes are used for providing additional information about HTML elements. All HTML elements can have attributes. Attributes are always defined in a start tag. It consists of name-value pair.

e.g. Name='value'


### Headings

HTML headings are titles or subtitles that we want to display on a webpage. HTML headings are defined with ```<h1></h1>``` to ```<h6></h6>``` tags.

### Paragraphs

A paragraph always starts on a new line, and is usually a block of text. Paragraph automatically removes extra space and lines when the page is displayed.

- ```<pre></pre>``` is used for preformatted text.

- ```<hr>``` is used for horizontal lines. It is an empty tag that's why end tag is not required.

- ```<br>``` is used for line breaks. It is an empty tag that's why end tag is not required.

- ```&nbsp;``` is used for adding single space in between paragraphs.

- ```&emsp;``` is used for tag space in between paragraphs.

### Styles

The HTML **style** attribute is used to add a style to an element, such as color, font, size & more.

### Formatting

HTML contains several elements for defining text with a special meaning.

- ```<b>```: Bold
- ```<i>```: Italic
- ```<u>```: Underline
- ```<q>```: Quotation
- ```<blockquote>```: Block Quote
- ```<em>```: Emphasis
- ```<mark>```: Highlighted Text
- ```<small>```: Small Text
- ```<del>```: Delete Text
- ```<ins>```: Insert Text
- ```<sub>```: Subscript
- ```<sup>```: Superscript
- ```<strong>```: Important Text
- ```<abbr>```: Abbreviation
- ```<cite>```: Title of creative work
- ```<address>```: Address
- ```<bdo>```: Bi-Directional Overwrite

### Comments
In HTML, we write comments in between ```<!--Comment-->```