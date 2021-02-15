<style>
    h1,h2,h3,h4,h5,h6 {color: black; padding: .25em}
    h1 {background: lightpink}
    h2 {background: lightsalmon}
    h3 {background: lightyellow}
    h4 {background: lightgreen}
    h5 {background: lightblue}
    h6 {background: plum}
</style>

# Webdev1 - Week 4 - 02/15/21
## CSS Part 2: CSS Selectors, Sizing Units, Positioning part 1., and Background Images

## Agenda
### **Part I: Getting Started**
#### 1. **Hellos**
   1. Close other apps
   2. Ask questions
   3. Office hours this week
#### 2. **Last week recap/go over homework**
   1. Separate Document CSS
   2. CSS Box Model

### **Part II: New CSS Concepts**
#### 0. **Setting up our coding environment**
   1. Open VS Code
   2. For each new concept, we will create a new folder. Each folder will contain an `index.html` and a `style.css` file. **You can copy and paste your folders each time.**
#### 1. **CSS Selectors**
*How do we target specific sections of our code?*
[List of CSS Selectors](https://www.w3schools.com/cssref/css_selectors.asp) (W3 Schools)
   1. Classes .
   2. IDs #
   3. "Utility classes"
   4. Order of selector importance (ID > Class > Element)
#### 2. **CSS Units**
[List of CSS Units](https://www.w3schools.com/cssref/css_units.asp) (W3 Schools)
   1. `px` (pixels, avoid using these) 
   2. `em`
   3. `rem`
   4. `%`
   5. `vw` (viewport *width*)
   6. `vh` (viewport *height*)
   7. `vmin` (This is a good one!)
   8. `vmax` (rarely used)
   9. `%` (relative to the size of the parent element)

#### 3. **CSS Display properties**
*We already know some of these from our intro to HTML*
   1. display: block;
   2. display: inline;
   3. display: inline-block;

#### 4. **CSS Positioning (part 1)**
*[CSS Positioning Guide](https://www.w3schools.com/css/css_positioning.asp) (W3 Schools)*
   1. `position: static;` (this is the default)
   2. `position: absolute;`
   3. `position: fixed;`
   4. (we'll cover position: relative and position: sticky next week)
   5. Centering your content ([Centering in CSS: A Complete Guide](https://css-tricks.com/centering-css-complete-guide/) (CSS-Tricks))
      1. text-align: center;
      2. margin: 0 auto;
        ```
        my-element { 
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
        }
        ```
      3. Use padding to center your content vertically!

#### 5. **Images and GIFs**
   1. Creating folders for your image assets
   2. Adding images to our folders
   3. Renaming image files so they're easier to work with
      1. No spaces!
      2. lowercase letters!
      3. Consistent extensions (rename 'jpeg' to 'jpg')
      4. .jpg, .png, .gif are all fine
      5. Small file sizes!
      6. Set image size in your CSS, *__not in your HTML__*

#### 6. **Homework**
   1. Coding Assignment: Create your own "Geocities"/"Web 1.0" web page.
      1. Find gifs on [gifcities.org](https://gifcities.org)
   2. Tutorial Assignment: FreeCodeCamp: Complete tutorials 1-22, 24-25 (Starting with 'Create Visual Balance Using the text-align Property' and ending with 'Center an Element Horizontally Using the margin Perperty') in the 'Applied Visual Design' Section. Note: Do NOT do Tutorial 23 (The one with floats)
   3. Read Assignment (Optional): [Rich User Experience, UX and Desktopization of War](http://contemporary-home-computing.org/RUE/) (2014) - Olia Lialina & Dragan Espenschied
      1. [Olia Lialina's website](http://art.teleportacia.org/) (Look at that absolute positioning!)
    



