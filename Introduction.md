# Introduction to HTML

![Webpage Cake](https://mdn.mozillademos.org/files/13502/cake.png)

## HTML DEFINED

1.  **What is HTML?**
    * HTML **(Hypertext Markup Language)** is not a programming language; it is a markup language used to tell your browser how to structure the web pages you visit.
    * HTML consists of a series of elements, which you use to enclose, wrap, or mark up different parts of the content to make it appear or act a certain way.
    * Browsers **don't display HTML tags**, but use them to display content on the webpage. (SHOW EXAMPLE WEBPAGE AND HTML TAGS)

## OBJECTIVE

1.  Define HTML.
2.  What does a HTML element consist of?
3.  What are examples of HTML tags?
4.  Where do our HTML elements live?

## OPENING EXERCISE (10 MINS)

1.  Let's warm up our fingers with a general typing exercise: https://www.typingtest.com/test.html?minutes=2&textfile=oz.txt
2.  Now, lets do a HTML typing exercise: http://www.speedcoder.net/lessons/html/1/

# INTRODUCTION TO HTML

## ANATOMY OF AN HTML ELEMENT

1.  In https://codepen.io/pen/ in the **HTML** section lets type:

```html
My cat is very grumpy
```

2.  If we wanted the line to stand by itself, we could specify that it is a **paragraph** by enclosing it in paragraph **`(<p></p>)`** tags:

```html
<p>My cat is very grumpy</p>
```

Let's explore our paragraph element a bit further:

![HTMLElement](https://mdn.mozillademos.org/files/9347/grumpy-cat-small.png)

The main parts of our element are:

1.  **The opening tag:** This consists of the name of the element (in this case, p), wrapped in opening and closing angle brackets. This states where the element begins or starts to take effect.
2.  **The closing tag:** This is the same as the opening tag, except that it includes a forward slash before the element name. This states where the element ends. **Failing to include a closing tag is a common beginner error and can lead to strange results.**
3.  **The content:** This is the content of the element, which in this case is just text.
4.  **The element:** The **opening tag** plus the **closing tag** plus **the content** equals the element.

## NESTING ELEMENTS

You can put elements inside other elements too — this is called **nesting**. If we wanted to state that our cat is **very** grumpy, we could wrap the word "very" in a `<strong>` element, which means that the word is to be strongly emphasized:

```html
<p>My cat is <strong>very</strong> grumpy.</p>
```

You do however need to make sure that your elements are properly nested: in the example above, **we opened the p element first**, **then the strong element**, **therefore we have to close the strong element first**, **then the p**. The following is incorrect:

```html
<p>My cat is <strong>very grumpy.</p></strong>
```

The **elements have to open and close correctly**, so they are clearly inside or outside one another.

## A SIMPLE HTML DOCUMENT

```html
<!DOCTYPE html>
<html>
<head>
<title>Page Title</title>
</head>
<body>

<!–– THIS IS WHERE YOUR HTML ELEMENTS LIVE ––>
<!–– BETWEEN THE <body></body> TAGS ––>

</body>
</html>
```

### DOCUMENT EXPLAINED

* The `<!DOCTYPE html>` declaration defines this document to be HTML5
* The `<html>` tag is the root element of a HTML page
* The `<head>` tag contains meta information about the document
* The `<title>` tag specifies a title for the document
* The `<body>` tag contains the visible page content

## 🚨 INDEPENDENT ACTIVITY 🚨

### USING THE HTML DOCUMENT ABOVE: WRITE A PARAGRAPH ABOUT YOURSELF (BETWEEN THE <body></body> tags), USING THE HTML TAGS WE LEARNED (BELOW WE HAVE MORE EXAMPLES OF HTML TAGS) OR ANY OTHER TAGS YOU MAY KNOW. 🙋 RAISE YOUR HAND IF YOU NEED HELP.

## MORE EXAMPLES OF HTML TAGS

```html
The HTML <h1>–<h6> elements represent six levels of section headings. <h1> is the highest section level and <h6> is the lowest.
<h1>, <h2>, <h3>, <h4>, <h5>, <h6>
```

```html
Renders text with a strikethrough, or a line through it.
<s>
```

```html
Defines smaller text
<small>
```

```html
Defines important text (bold)
<strong> or <b>
```

```html
Italic
<em>
```

```html
Underline
<u>
```

```html
An unordered list with 4 items. Each item is contained in a <li></li>
<ul>
<li></li>
<li></li>
<li></li>
<li></li>
</ul>
```

```html
An ordered list with 4 items. Each item is contained in a <li></li>
<ol>
<li></li>
<li></li>
<li></li>
<li></li>
</ol>
```

## REVIEW OF HTML ELEMENTS

* HTML tags normally come in pairs like `<p>` and `</p>`
* The first tag (opening tag) in a pair is the start tag, the second tag (closing tag) is the end tag.
* The end tag is written like the start tag, but with a **forward slash inserted before the tag name**.

### QUESTIONS 🚨

1.  What are examples of HTML tags?
2.  What are the **3** components that make up a HTML element?
