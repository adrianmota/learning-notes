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
