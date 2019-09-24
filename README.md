# What I Learned In Week 2

### Intro to CSS
CSS stands for **Cascading Style Sheets**. It is a language that describes the style of an HTML document.
* We learned how to link external CSS with HTML with the following link:
  * `<link rel=”stylesheet” type=”text/css” href=“style.css”/>`
* Your CSS style goes inside the style tag, and always on inside the head tags
* CSS properties are set with a property and value.
  * `font-size: 40px;`
* CSS rules are written by indicating a selector.
  * The three selector types are tag, .class, and #id's.
* A few selector combinations are:
  * Apply to all: h1, div, p
  * Apply to descendants: div p
  * Apply to direct descendants: div > p

---
### Ugly-Webby
This was our first CSS project. Instead of trying to make a website look nice, we had to play around and mess it up. 

---
### Copy-Kitten
The project entailed copying three images with CSS. The three sections to copy were **the button, the header, and the table**. The challenge was learning new features in CSS and implementing them in our CSS.
* Used the **pseudo-selector** `inset-shadow` for a neat effect on the button when its clicked.
* The `text-transform` property lets you make all the letters either lowercase, uppercase, or capitalize (the first letter of each word).
* I learned the `display` function to change the header horizontal and back to vertical.
* You can add the hover feature by specifying the selector.
  * `p:hover {background-color: red; }`
* There are different ways to add borders to items or text. Remember that it may be easier to set all borders and exclude certain ones.

---
### Copy-Calico
I took the challenge of copying the website "The Office of Jason James". At first glance, I saw a few challenges that I wanted to learn from this website.
* You are able to put dashes around a word (-Title -), by adjusting `margin-bottom-height` and moving the line up. 
* To find more information on the website, you can "inspect" the page. You will find information on font, font-size, color, and more.

---
### CSS Boxes 
There's an image of four red boxes with different borders around them that we have to replicate. It was challenging at first but adjusting the `background-clip` and adjusting the `padding` did the trick.

---
### Human Resource Machine (HRM) & CSS Diner
HRM is a challenging game that requires you to think outside the box. I like the build up of different tools and levels in the game. 

CSS Diner teaches you how to target specific **CSS selectors**. The game teaches you different concepts while giving you a visual test.

---
### Intro to JavaScript (JS)
JS gives a website or app the ability to "function". 
* Variables are containers for storing data values.
  * You can declare variables by using `let` or `const`.
* JS primitive data types are:
  * Strings, Numbers, Booleans, NaN, Null, Undefined.
