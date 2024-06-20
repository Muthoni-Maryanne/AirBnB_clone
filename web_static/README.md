# 0x01. AirBnB clone - Web static

## Background Context

Now that you have a command interpreter for managing your AirBnB objects, it’s time to make them alive! Before developing a big and complex web application, we will build the front end step-by-step. The first step is to “design” / “sketch” / “prototype” each element:

- Create simple HTML static pages
- Style guide
- Fake contents
- No Javascript
- No data loaded from anything
- During this project, you will learn how to manipulate HTML and CSS languages. HTML is the structure of your page, it should be the first thing to write. CSS is the styling of your page, the design.

## Resources
1. [Learn to Code HTML & CSS (until “Creating Lists” included)](https://learn.shayhowe.com/html-css/)

## Summary
Example:

HTML:
```
<!DOCTYPE html>
<html lang="en">
        <head>
                <meta charset="utf-8">
                <title>Styles conference</title>
                <link rel="stylesheet" href="assets/stylesheets/main.css">    #link to CSS file
        </head>
        <body>
                <h1>Styles conference</h1>
                <p>Every year the brightest web designers and front-end developers descend on Chicago to discuss the latest technologies. Join us this August!</p>
        </body>
</html>
```
CSS ([Eric Meyer reset](https://meyerweb.com/eric/tools/css/reset/)):
```
/* http://meyerweb.com/eric/tools/css/reset/ 2. v2.0 | 20110126
  License: none (public domain)
*/

html, body, div, span, applet, object, iframe,
h1, h2, h3, h4, h5, h6, p, blockquote, pre,
a, abbr, acronym, address, big, cite, code,
del, dfn, em, img, ins, kbd, q, s, samp,
small, strike, strong, sub, sup, tt, var,
b, u, i, center,
dl, dt, dd, ol, ul, li,
fieldset, form, label, legend,
table, caption, tbody, tfoot, thead, tr, th, td,
article, aside, canvas, details, embed,
figure, figcaption, footer, header, hgroup,
menu, nav, output, ruby, section, summary,
time, mark, audio, video {
  margin: 0;
  padding: 0;
  border: 0;
  font-size: 100%;
  font: inherit;
  vertical-align: baseline;
}
/* HTML5 display-role reset for older browsers */
article, aside, details, figcaption, figure,
footer, header, hgroup, menu, nav, section {
  display: block;
}
body {
  line-height: 1;
}
ol, ul {
  list-style: none;
}
blockquote, q {
  quotes: none;
}
blockquote:before, blockquote:after,
q:before, q:after {
  content: '';
  content: none;
}
table {
  border-collapse: collapse;
  border-spacing: 0;
}
```
## Learning Objectives

- What is HTML
- How to create an HTML page
- What is a markup language
- What is the DOM
- What is an element / tag
- What is an attribute
- How does the browser load a webpage
- What is CSS
- How to add style to an element
- What is a class
- What is a selector
- How to compute CSS Specificity Value
- What are Box properties in CSS

## Requirements- General

- Allowed editors: vi, vim, emacs
- All your files should end with a new line
- A README.md file, at the root of the folder of the project, is mandatory
- Your code should be W3C compliant and validate with W3C-Validator
- All your CSS files should be in styles folder
- All your images should be in images folder
- You are not allowed to use !important and id (#... in the CSS file)
- You are not allowed to use tags img, embed and iframe
- You are not allowed to use Javascript
- Current screenshots have been done on Chrome 56 or more.
- No cross browsers
- You have to follow all requirements but some margin/padding are missing - you should try to fit as much as you can to screenshots
