# HTML

## What is HTML?

HTML stands for **HyperText Markup Language**, this is the language used to define the web pages structure, the meaning of the information presented, and the semantical structure as well.

HTML is a standard of the web, this means that all the web browsers have to adapt to this technology. If a new feature is added to HTML language specification, all the browsers have to add that feature to maintain the compatibility, although not all the browsers implement the new features, for example *Internet Explorer*.

HTML was developed in the first place by Tim Berners-Lee in 1991, the creator of the web, but the official released was in 1993, and was intended to extend the SGML (Standard Generalized Markup Language), but then HTML became the standard of the web. This language was intended to make easier the tranmission of the information between scientists and the W3C has been adding new features since then.

## What is HTML for exactly?

This language is used to describe or define the structure of a web page, meaning that the information displayed in a web browser can be presented in a logical and particular way by using HTML elements.

## What is an HTML element?

An HTML element is like an object that is used to represent information in a way or another. Text, videos, images, audio, etc., can be presented in the document using HTML elements defined for that purpose. An HTML element is defined using *tags*. Tags are compound by ankle brackets and a word that describes the element itself, and almost all the HTML elements have an opening and closing tag.

This is an example:
```html 
<p></p>
```
The first one is the opening tag, and the last one is the closing tag.

An HTML element has two properties, the *content* and the *attributes*.

The content is the text or elements that are between the opening and closing tag. Also it is the information that is displayed in the web browser.

For example:
```html
<p>This is a paragraph</p>
```
The text between the opening and closing tag *This is a paragraph* is the content.

The attributes are aditional information about the element, but not information displayable necessarily. Specifically they are name-value pairs, separated by the equal sign =. This information can be used to affect the element to add styles using CSS or to change its behavior using JavaScript.

For example:
```html
<p class="bold">This text is in bold</p>
```

In the last example we could see that the element has a class attribute, with a value of *bold*, and it can be used by CSS to add styles to that element, or used by JavaScript to affect the element dynamically.

This is another example:
```html
<h1 id="heading">My Heading</h1>
```

In the last case, the id attribute is used to identify an element in an unique way, which means that there shouldn't be other elements with the same attribute value, and this is used to afect the element adding styles to it using CSS or changing its behavior with JavaScript.

Not all the elements in HTML has content in them, for example:
```html
<br/>
```

Note: All the HTML elements are not case sensitive, this means that it's the same writing \<title\>, \<Title\> or \<TITLE\>, but the recommendation is to write HTML in lower case.

Let's take a look at a basic HTML page:
```html
<!DOCTYPE html>
<html>
  <head>
    <title>My web page</title>
  </head>
  <body>
    <h1>My first web page</h1>
    <p>Hi, I'm Adrian Mota</p>
  </body>
</html>
```

In the last example, we could see a basic HTML page, and I will explain each part of that.

## The DOCTYPE declaration

At the beginning of the page, we saw like a tag, but it's not a tag, it is a type declaration. HTML has evolved from multiple versions, and now we are working with the last version which is HTML5, and first we have to indicate that the following lines are HTML code, and that the HTML version is the last, this is used to indicate the browsers that the page works with the latest features of HTML, and to help the browsers show the web pages correctly.

Many websites use previous versions of HTML, so, the modern browsers have to deal with previous versions of HTML due to the compatibility. That said, each time we create a new web page, we have to define the type declaration of the document, that indicates that the file is an HTML file and that it's using the lastest HTML version.

Always include at the beginning of all the web pages the type declaration:
```html
<!DOCTYPE html>
```

## Headings

HTML is used to define the struture and meaning of the information, so to define the different sections of topics, subtopics and so on, we use the heading elements. The heading elements are compound of 6 levels, from level 1 which is the most important to level 6 which is the least important. From up to bottom is recommendable using the most important level to the least important level.

Example:
```html
<h1>This is heading 1</h1>
<h2>This is heading 2</h2>
<h3>This is heading 3</h3>
<h4>This is heading 4</h4>
<h5>This is heading 5</h5>
<h6>This is heading 6</h6>
```

Note: don't confuse the different levels of headings with size, the headings are used to give meaning, if we only want to use the headings because of the size, we must use CSS to change the size of the text instead of using headings.

## Nested HTML elements

An HTML page is compound of nested elements. Nested elements means that there are elements into another elements.

For example:
```html
<!DOCTYPE html>
<html>
  <body>
    <h1>This is a Heading</h1>
    <p>This is a paragraph.</p>
  </body>
</html>
```

In the last example we could see that there are HTML elements into other HTML elements, like *h1* inside *body*, and *body* inside *html*, and so on.

But let's explain this basic elements:
- \<html\>: it's the root element of the page, which represents the whole document. In it are defined the rest of the elements.
- \<body\>: it's the body element of the page, this represents the visible content of the web page. It goes inside the \<html\> element.
- \<h1\>: it's the level 1 heading, which is the most important heading in a page.
- \<p\>: it's the paragraph element, which represents a paragraph semantically.

## Attributes

Let's talk about some attributes. As we said before attributes are additional information about the elements. These give that information to affect the element in one or another way.

When we use an \<a\> tag, it is to create a hyperlink, and the attribute made for that purpose is *href* which stands for hypertext reference, where as a value you define an absolute or relative URL to the page that the hyperlink points to. 

```html
<a href="https://www.wikipedia.org">Visit wikipedia.org</a>
```

As the example above, this is done to define the page that the hyperlink points to, once clicked over the hyperlink we get that page in the browser's screen.

Another example with images, the \<img\> tag is used to embed images in the HTML document, using the *src* attribute, and we define an alternative text that is shown in case the image isn't loaded because it was not found, the URL is wrong, slow connection, the client is not a visual browser, etc.

```html
<img src="my_image.jpg" alt="Some image">
```

As we could see, the *src* attribute is very important, because it gives the information about where the image is located, and the alternative as well, because of the accessibility.

There is much more examples out there, but the main idea is that the attributes are very important when defining the HTML elements.

## Formatting in HTML

In HTML we can give format to the text, with the purpose of transmitting some information semantically, or simply give a different look to the text.

Some of the elements that are used to do this are the following:

- \<b\>: this element makes the text **bold**.
- \<strong\>: this element indicates that the text is important, and also makes the text **bold**.
- \<i\>: this element is used for making the text *italic*, denote phrases in other languages, change the voice of the text when using screen readers, and so on.
- \<em\>: this element emphasizes the text. Also it makes the text italic.
- \<sub\>: this element takes the text a half character under the normal text, it's useful when defining chemical formulas.
- \<sup\>: this element takes the text a half character over the normal text, it's useful for some expressions like math equations.
- \<del\>: this element indicates that the text has been deleted from the document.
- \<ins\>: this element indicates that the text has been inserted into the document.
- \<mark\>: this element is used to mark a text.
- \<small\>: this element is used to denote text that is smaller than the text around, and its size is relative to the size of the text around, for example, if it's defined inside a paragraph with a specific size, the size of the element's text <\small\> will be set according to the paragraph' size.

## HTML quotations

There are multiple ways of making quotations in HTML, among those we have the following:

- \<q\>: this is used for making short quotations.
- \<blockquoute\>: this is used for making quotations that are from another source. In this element, we specify the source of the quote with the *cite* attribute.
- \<cite\>: this is used to make reference to the name of artistic work, like movie's name, songs, paints, etc.
- \<bdo\>: this is used to change the direction of the text. Useful for those languagues where they write from right to left. We use the *dir* attribute to specify the direction of the text.
- \<address\>: this is used to specify personal information of an author of a document or an owner, like email, name, location, phone number, etc.
- \<abbr\>: this is used to specify abbreviations in the page. Useful for browsers, translation systems and search engines. Important to specify the description of the abbreviation using the *title* attribute.
