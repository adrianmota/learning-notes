# HTML

## What is HTML?

HTML stands for **HyperText Markup Language**, this is the language used to define the web pages structure, the meaning of the information presented, and the semantical structure as well.

HTML is a standard of the web, this means that all the web browsers have to adapt to this technology. If a new feature is added to HTML language specification, all the browsers have to add that feature to maintain the compatibility, although not all the browsers implement the new features, for example *Internet Explorer*.

HTML was developed in the first place by Tim Berners-Lee in 1991, the creator of the web, but the official released was in 1993, and was intended to extend the SGML (Standard Generalized Markup Language), but then HTML became the standard of the web. This language was intended to make easier the tranmission of the information between scientists and the W3C has been adding new features since then.

## What is HTML for exactly?

This language is used to describe or define the structure of a web page, what does it mean exactly?, it means the information that is presented in a web browser can be presented in a logical and particular way by the use of HTML elements.

## What is an HTML element?

An HTML element is like an object that is used to represent information in a way or another. Text, videos, images, audios, etc., can be presented in the document using HTML elements defined to that purpose. An HTML element is defined using *tags*. Tags are compound by ankle brackets and a word that describes the element itself, and almost all the HTML elements have an opening and closing tag.

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

Anothe example is this:
```html
<h1 id="heading">My Heading</h1>
```

In the last case, the id attribute is used to identify an element in an unique way, which means that shouldn't be others elements with the same attribute-value, and this is used to afect the element adding styles to it using CSS or changing its behavior with JavaScript.

Not all the elements in HTML has content in them, for example:
```html
<br/>
```
This type of elements are called empty elements, which have no content and a closing tag. Another example of that is the following:
```html
<img src="./images/photo.jpg" alt="An image" />
```
In the last case, we can see that the *img* element has no content defined, but this because we don't define that content by ourselves, in that case the browser is the responsible for that, by the src attribute we only specify the relative or full path of the image, and the browser knows how to show it in the page.

Note: All the HTML elements are not case sensitive, this means that it's the same write title, Title or TITLE, and so on, but the recommendation is to write HTML in lowe case.

Let's take a look to a basic HTML page
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

In the last example, we could see a basic HTML page, and I will explain each part of that:

## The DOCTYPE declaration
At the beginning of the page, we saw like a tag, but it's not a tag, it is a type declaration, what does it mean?, HTML has evolved from multiple versions, and now we are working with the last version which is HTML5, and first we have to indicate that the following lines are HTML code, and that the HTML version is the last, this is used to indicate the browsers that the page works with the latest features of HTML, and to help the browsers show the web pages correctly.

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

Note: don't confuse the different levels of headings with size, the heading are used to give meaning, if we want only use the headings because of the size, we must use CSS to change the size of the text instead using the headings.
