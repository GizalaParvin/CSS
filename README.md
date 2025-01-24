CSS

Table of Contents

1.CSS Basics

  Box Model

  Overflow

  Shadows

2. CSS Layouts

  Flexbox

  Grid

3. CSS Effects

  Hover Effects

  Transitions and Animations

4. Navigation Bars

5. Card Designs

6. Projects

7. Conclusion


CSS Basics

Box Model

What it is: Defines how the elements' width and height are calculated: content + padding + border + margin.

Key Properties: margin, border, padding, width, height.

    .box {
         width: 200px;
        padding: 10px;
        border: 2px solid black;
        margin: 20px;
          }

Overflow

What it does: Handles how content overflows an element's box.

Values: visible, hidden, scroll, auto.

     .overflow-example {
       width: 300px;
     height: 100px;
     overflow: auto;
      }

Shadows

Box Shadow: Adds shadow effects to elements.

Text Shadow: Adds shadow to text.

    .box-shadow {
     box-shadow: 5px 5px 10px rgba(0, 0, 0, 0.5);
     }

    .text-shadow {
     text-shadow: 2px 2px 5px #888;
    }

    Projects

CSS Layouts

Flexbox

What it is: A layout module that provides a flexible way to align and distribute space.

Key Properties: display: flex, justify-content, align-items, flex-direction.


       .container {
        display: flex;
        justify-content: center;
        align-items: center;
        height: 100vh;
     }

Grid

What it is: A powerful 2D layout system.

Key Properties: display: grid, grid-template-columns, grid-template-rows, gap.

      .grid {
       display: grid;
        grid-template-columns: repeat(3, 1fr);
         gap: 20px;
      }

CSS Layouts

Flexbox

What it is: A layout module that provides a flexible way to align and distribute space.

Key Properties: display: flex, justify-content, align-items, flex-direction.

            .container {
                display: flex;
                 justify-content: center;
                 align-items: center;
                 height: 100vh;
         }

CSS Effects

Hover Effects

What it is: Style changes when the user hovers over an element.

Examples: Button hover, image hover zoom.

    .button:hover {
       background-color: #4CAF50;
         color: white;
      }
Navigation Bars

Description: Create responsive and stylish navbars using Flexbox or Grid.

     <nav class="navbar">
       <ul>
          <li><a href="#">Home</a></li>
           <li><a href="#">About</a></li>
           <li><a href="#">Contact</a></li>
       </ul>
    </nav>

    <style>
      .navbar {
            display: flex;
            justify-content: space-around;
            background-color: #333;
            padding: 10px;
       }
           .navbar a {
            color: white;
            text-decoration: none;
       }
            .navbar a:hover {
            text-decoration: underline;
         }
           </style>  

1. CSS Calculator

A simple calculator designed with CSS for buttons and layout.

2. To-Do List

Style a dynamic to-do list with hover and click effects.

3. Landing Page

Build a responsive landing page with grid or flexbox layouts.

4. Interactive Navbar

Create a responsive navbar with dropdown menus and hover effects.

Conclusion

This CSS Handbook is just the beginning. Keep experimenting and exploring! For more resources, check out MDN Web Docs or CSS Tricks. Happy coding! 🎨


