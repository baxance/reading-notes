# Design web pages with CSS

### Overview of CSS
CSS is the trim package added to the bare frame that is HTML. Muscle and skin laid atop your skeleton of HTML.

CSS code has its own set of rules and elements that can be attached to specific HTML elements. For example

- A CSS Rule contains a *Selector* that tells the code which HTML element the following declaration applies to.
- A CSS *Declaration* indicates what styling can be applied to that specified HTML element

```
p{font-family: Arial;}
```
- The p in the sample above is the Selector and the text within the curled brackets { } is the Declaration

To further elaborate on declarations there are two parts to them within each set of brackets.

- The *Property* which specifies what aspects of the HTML element you wish to change
- The *Values* which specify the settings you wish to use.
- In the brackets in the code sample "font-family" is the property and "Arial" would be the value.

CSS can be attached to your HTML throuh internal or external means, by adding a link to the CSS file within your code (external) or by simply adding the CSS code you wish to use directly within yout HTML. External implementation of CSS is typically better when you are creating multiple pages that you want all of the CSS rules to apply to similarly, while adding CSS in-line with your HTML can be quicker when you're only creating a single page.

### Color

One of the simplest ways of dressing up your website is through the use of color. It can also help you direct the users attention to what is most important on the page through gradiants and blocking that draw the eyes to points of importance or subconsciously tell the reader what is similar.

- You can specify colors through CSS using *RGB Values*, *Hex Codes*, and simple *Color Names*.
```
h1 {color: rgb(100,100,100);}
h2 {color: #ee3e80;}
h3 {color: Blue;}
```
- Create contrast between your background and your text make it pop, or at the very least make it easy to read
 


[<== Back to Readme](README.md)