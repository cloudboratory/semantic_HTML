# Semantic HTML Exerscise

[![HTML5](https://upload.wikimedia.org/wikipedia/commons/thumb/6/61/HTML5_logo_and_wordmark.svg/260px-HTML5_logo_and_wordmark.svg.png)](https://upload.wikimedia.org/wikipedia/commons/thumb/6/61/HTML5_logo_and_wordmark.svg/260px-HTML5_logo_and_wordmark.svg.png)

## Background

A semantic element clearly describes its meaning to both the browser and the developer.
Examples of non-semantic elements: `<div>` and `<span>` - Tells nothing about its content.
Examples of semantic elements: `<form>`, `<table>`, and `<article>` - Clearly defines its content.

In this exercise you will modify non-semantic HTML into its semantic equivalent.

## The exercise

[![HTML5 structure](https://www.jungledisk.com/blog/content/images/blog/div-soup-vs-semantic-html.png)](https://www.jungledisk.com/blog/content/images/blog/div-soup-vs-semantic-html.png)

In this quick exercise, you will write the HTML code for the webpage wireframes above. 

First, you will code the wireframe on the left using non-semantic HTML, then you will code the wireframe on the right using semantic HTML. As you code the wirefram on the right, make sure to refer to the [MDN HTML element reference](https://developer.mozilla.org/en-US/docs/Web/HTML/Element) to understand the intended use of each semantic tag. 

## Instructions

1. Create two .html files in your text editor or IDE. Name them "non-semantic.html" and "semantic.html" respectively. Copy the below HTML bolierplate into your files to get you started.
```
    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <title>Semantic HTML5</title>
    </head>
    <body>
    <!--insert your code here-->
    </body>
    </html>
```
2. In the "non-semantic.html" file, write the HTML for the non-semantic wireframe. Feel free to add "meaning" to the HTML by using HTML element attributes such as "id" and "class". It should resemble the code below. 
```
    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <title>Semantic HTML5</title>
    </head>
    <body>
        <div class="header">
            <span class="navigation">
            </span>
        </div>
        <div class="article">
            <div class="figure">
            </div>
        </div>
        <div class="footer">
        </div>
    </body>
    </html>
```
3. Repeat the process, but this time use semantic HTML tags. In the "semantic.html" file, write the HTML for the semantic wireframe. No example provided this time!

4. Once you've completed the exercise, commit both files to your github.

## Summary and additional resources

Using HTML5 semantic tags in your code provides the following advantages:

- Easier to read - reduces cognitive load of developers
- Greater accessibility - search engines and assistive technologies (like screen readers for users with a sight impairment) are able to understand the context and content of your website, meaning a better experience for your users
- Consistent code -  different programmers might write a header like this as `<div class="header">`, `<div id="header">`, `<div class="head">`, or simply `<div>`. By using a standard semantic element, it creates a consistent style.
- SEO - Search engines will consider contents within semantic elements as important keywords that influence the page's search rankings

To learn more about semantics in web development visit the MDN [sematics reference article](https://developer.mozilla.org/en-US/docs/Glossary/Semantics). 
