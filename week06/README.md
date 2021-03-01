<style>
    h1,h2,h3,h4,h5,h6 {color: black; padding: .25em}
    h1 {background: lightpink}
    h2 {background: lightsalmon}
    h3 {background: lightyellow}
    h4 {background: lightgreen}
    h5 {background: lightblue}
    h6 {background: plum}
</style>

# Webdev1 - Week 5 - 02/22/21
## CSS Flexbox: Making more advanced layouts, centering your content

## Agenda
### **Part I: Getting Started**
#### 1. **Hellos**
   1. Close other apps
   2. Look over your comments/grades
      1. Late policy reminder: Assignments more than a week old can still be turned in for up to 5 points.
   3. Ask questions
   4. Office hours this week (Thursday, 03/04, 5pm-7pm). This time slot is open to both sections, so you may see students in other sections, but we're all working on the same material!

### **Part II: New CSS Concepts**
#### 0. Review last week's concepts
  1. `position: absolute;`
  2. `position: fixed;`
  3. `position: relative;`
  4. `position: sticky;`


#### 1. **Setting up our coding environment**
   1. Open VS Code
   2. For each new concept, we will create a new folder. Each folder will contain an `index.html` and a `style.css` file.

#### 2. **Centering in CSS**
[Centering in CSS: A Complete Guide (CSS Tricks)](https://css-tricks.com/centering-css-complete-guide/)
   1. `text-align: center;`
   2. `margin: 0 auto;`
   3. `position: absolute;` (or fixed, or relative)
      1. `left: 50%;`
      2. `top: 50%;`
      3. `transform: translate(-50%, -50%);`
   4. `position: absolute;` (or fixed, or relative) (note, for this one, the important thing is that the left and right are equal to each other, and the top and bottom are equal to each other. I just chose 20% and 10% randomly, here)
      1. `left: 20%;`
      2. `right: 20%;`
      3. `top: 10%;`
      4. `bottom: 10%;`
   5. `padding: 2em;` (making an element with equal padding on all sides will put your text in the center of the element.
   6. `display: flex;` (CSS Flexbox!)

#### 3. **CSS Flexbox**
*[CSS Positioning Guide](https://www.w3schools.com/css/css_positioning.asp) (W3 Schools)*
   1. `position: relative;`
   2. `position: sticky;`

#### 5. **Images and GIFs**
   1. Linking to images on the web
   2. Using [picsum.photos](https://picsum.photos/) for stock photos
   
#### 6. **Homework**
   1. 5a: Freecodecamp tutorials (coming soon)
   2. 5b: Coding Assignment: re-create [this web page](https://www.theverge.com/22258257/flight-attendants-history-covid-pandemic-airline-industry-aviation)
    