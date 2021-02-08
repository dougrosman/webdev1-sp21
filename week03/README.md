# Webdev1 - Week 3 - 02/08/21
## CSS Basics, CSS Box Model

### Outline
1. Beginning of class must-dos (close other apps, make sure firefox is ready to go)
2. Recap from last week (HTML elements, inline vs. block, indenting, semantic html, html validator)
3. GitHub Desktop
4. Cloning with git/GitHub
5. setting up a web project in VS Code, working with Live Server
6. Intro to CSS (Cascading Style Sheets)
   1. inline style (don't do this), in-document style (more acceptible, but don't do this for this class)
   2. good formatting, semicolons
   3. element selectors
   4. different colors (built-in, rgb, hex)
7. CSS Box model
   1. Content
   2. Padding
   3. Border
   4. Margin
8. Shorthand (putting all the different margin numbers on the same line)
9. Importing fonts from Google Fonts
10. sizing units (px, em, rem, %, vw, vh);



#### HTML-only websites
From https://1mb.club/
* https://madeyoulook.lol/
* https://crouton.net/
<hr>
<br>
<br>

# Day 02, 02/01/21 - Learning HTML

<hr>

### Quick reference: In-class exercises
1. [Indenting your code to make it more readable](indentation) [*[download the starter code](indentation.zip)*]
2. [Fixing Code with an HTML Validator](html_validator) [*[download the starter code](html_validator.zip)*]
<hr>

## Agenda
1. Hellos/Last week recap
    1. Taking attendance after class based on Zoom numbers
    1. In order to be marked on time, you must be in the Zoom waiting room by the class start time (12:30);
    1. If you miss over 30 minutes of class, you will be marked absent for the day.
    <hr>
    
1. What is HTML?
    1. Turn off CSS styling in Firefox (View --> Page Style --> No Style)
    1. Open a web page and view source [crouton.net](https://crouton.net)
        * Command+U (Mac)
        * CTRL+U (Windows)
    1. The [DOM (Document Object Model)](https://developer.mozilla.org/en-US/docs/Web/API/Document_Object_Model/Introduction)
    ![DOM Diagram](https://simplesnippets.tech/wp-content/uploads/2018/10/what-is-document-object-model-in-JS-featured-image.jpg)
    1. Required elements (click here to view a [basic HTML page](basic_html_document))
        * &lt;DOCTYPE! html&gt;
        * &lt;html&gt;
        * &lt;head&gt;
            * &lt;title&gt;
        * &lt;body&gt;
    1. Open Codepen.io
    1. Open fresh Pen called 2.1-HTML Basics(S04-2.1_HTML)
    1. Go over basic HTML elements/tags
   
   ![HTML element diagram](https://wikimedia.org/api/rest_v1/media/math/render/svg/37506127f0730d9b6035530f46c706af4e2319d4)

     1. Block vs inline vs inline-block level elements
     2. headers:
         1. &lt;h1&gt;
         2. &lt;h2&gt;
         3. &lt;h3&gt;
         4. &lt;h4&gt;
         5. &lt;h5&gt;
         6. &lt;h6&gt;
     3. paragraph: &lt;p&gt;
     4. anchor (link): &lt;a&gt;
     5. &lt;div&gt;
     6. &lt;span&gt;
     7. &lt;header&gt;
     8. &lt;main&gt;
     9. &lt;footer&gt;
     10. &lt;nav&gt;
     11. &lt;section&gt;
     12. Lists:
         1. unordered list: &lt;ul&gt;
         2. ordered list: &lt;ol&gt;
         3. list item: &lt;li&gt;
     13. &lt;img&gt;
    1. HTML Attributes (things that go in the opening tab of an element, and are specific to that element)
        1. href (e.g. &lt;a href="https://crouton.net"&gt;)
        2. src (e.g. &lt;img src="https://picsum.photos/100&gt;)
        3. alt (e.g e.g. &lt;img src="https://picsum.photos/100&gt; alt="A cloudy forest with, mountain in the background)
        4. target (e.g. (e.g. &lt;a href="https://crouton.net" target="_blank"&gt;))
    <hr>
4. Semantic HTML and Accessibility
    1. Semantic HTML vs. Decorative HTML
    2. Making accessible web pages is incredibly important. Throughout the semester, we will discuss design approaches that work well for everyone.
    3. Using semantic HTML is incredibly important for making accessible web pages
    4. Screen readers
        1. [Watch: an example of a person using a screen reader](https://www.youtube.com/watch?v=dEbl5jvLKGQ)
    <hr>
2. Go over good coding habits
    1. Commenting your code
    2. Proper indentation:
        1. **In-class exercise** Complete the [Proper indentation exercise](indentation) by correctly indenting the elements in the code [*[download the starter code](indentation.zip)*]
    <hr>

3. How to troubleshoot (do these steps in this order) More information in the [How to Troubleshoot Guide](../guides/troubleshooting)
    1. Make sure your code is properly indented
    2. Look through your code to spot any errors
    3. Run your code through an HTML validator and correct any errors
    4. If you're still having issues, try googling the problem you're having
    5. If you're still having issues, reach out to a friend, a peer, a tutor, or me with your issue. Use the [Troubleshooting Guide](../guides/troubleshooting) to make sure you're asking questions in a way that best helps others to help you!
    6. **In-class exercise:** [Fixing Code with an HTML Validator](html_validator) [*[download the starter code](html_validator.zip)*]
    <hr>

    
5. Making your first web page!
    1. **In-class Exercise:** Invent a recipe for a made-up dish. Create a web page for that recipe that includes the following:
        1. A recipe title (hint, I'm not referring to the &lt;title&gt; tag--you don't need one of those tags in Codepen)
        2. An image
        3. A corny backstory
        4. An ingredients list
        5. A list of instructions

        Make sure to use semantic HTML (meaning, you should use the elements that make the most sense for each section! (e.g. &lt;header&gt;, &lt;main&gt;, &lt;footer&gt;). You should create the following page in a fresh Codepen called *HTML Recipe*
    <hr>
6. Discuss homework and where to find resources on Canvas
    1. HTML Basics Assignment: Creating a web page for a made-up business
    2. [Troubleshooting Guide](../guides/troubleshooting)

