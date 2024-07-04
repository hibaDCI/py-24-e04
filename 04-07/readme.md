# 04-07-24

### Website programming continued more
- unit size in css
- everything in html is a box(margin, padding,border)
- POST method in form 
- Publishing a page with GitHub pages
- intro into JS
### some resources 
Stack Overflow
https://www.w3schools.com/
[MDN Web Docs](https://developer.mozilla.org/en-US/)



### Box Model

Padding, margin, and the box model are fundamental concepts in CSS that dictate how elements are spaced and sized within a webpage.


#### Padding
Padding is the space between an element's content and its border. It's like an internal spacing that pushes the content away from the edges of the element. Padding is part of the element's box, affecting its size.



#### Border
The border is the line that encloses the padding and content of an element. It sits between the element's padding and margin. The border's width, style, and color can be controlled with CSS.



#### Margin
Margin is the space outside an element's border. It's like an external spacing that separates the element from neighboring elements or the document edge. Margins do not affect the element's size but the space around it.



# unit size in CSS
- Absolute Units: These are fixed-size units that are not affected by the parent element's size. 
- pixel : for minor adjustment like shadow , border

- Relative Units: These units are relative to other lengths. For example, percentage (%) is relative to the parent element's size, em is relative to the font size of the element, and rem is relative to the root element's font size.(useful for building layouts)
- Viewport Units: These are relative to the size of the viewport. Examples include viewport width (vw) and viewport height (vh),








<!-- I didn't reach to the this topic but your teacher will teach you most of these tomorrow  -->
<!-- Good luck and enjoy your course and see next time 😎 -->

# javascript

- Completely different from HTML and CSS 😊
- JavaScript was created in just 10 days.
-  Brendan Eich was the developer behind it.
-  JS adds dynamic functionality
-  JS can affect anything on your page
- #  JavaScript often waits for and reacts to events on the page
   - Something happens when a button is pressed
   - Something happens when the mouse moves over an element
   - Something happens when the page is done loading

```js
"example"
 
## Variables

- one of the most fundamental techniques of programming is the use of
        - names (identifiers) to represent values
- binding a name to value gives us way to use this value
 // Declare the "age" variable and assign it a value
    let age = 36

    // Assign the age variable a value
    age = age + 1


## Declaration with let and const

const C = 299792.548 // Speed of light (km/s)

 // Declare a new variable, assign a value
    // constants cannot change their value
    const name = "Rachel Carson"
    console.log(age)
    console.log(name)



   // This is called an object; basically grouped key-value pairs
    const majesticBeast = {
        type: "Felix Domesticus",
        name: "Rauli",
        age: 7.5,
        hungry: true,
    } 
    
    
## function

window.addEventListener("load",function(e){
    document.body.style.backgroundColor = "cyan"
  
})
document.getElementById("username").addEventListener("change", function() {

    if(this.value !== 'hello'){
        this.value = 'invalid-name';
    } 
     else {
        document.querySelector('.my-image').style.display = 'block'
     }
})

 
```