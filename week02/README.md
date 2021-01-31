# Webdev1 - Week 2 - 02/01/21
## HTML Basics + Troubleshooting

### Topics to cover
1. What is HTML/HTML5?
1. What is the DOM?
1. Elements and tags
1. Comments
1. Good habits (proper indentation)
1. Attributes
1. VS Code shortcuts
1. How to troubleshoot
    1. HTML Validator
    1. Errors (red text or squiggles)
1. How to ask questions
1. Semantic vs. decorative HTML
1. Accessibility and screen readers.
1. Cheatsheet

### Exercises
1. Turn off CSS styling in Firefox
1. Create a nested list
1. Correctly indent the nested elements
1. Fix all the errors in the validator
1. [open time] Invent a food dish, write some HTML that includes the recipe and some corny backstory.

### Homework
1. Using HTML only, create a web page for a fake business that you make up! What does your business offer? What sections and links does it have? The goal of this assignment is to build a semantic website. Create meaningful sections, and structure your HTML with the appropriate elements.
**Hints:** Look at regular websites with CSS turned off to see what type of content a website has, without being distracted by the styling.



#### HTML-only websites
From https://1mb.club/
* https://madeyoulook.lol/
* https://crouton.net/
___
<br>
<br>

# Day 02: Learning HTML

## Quick reference: In-class exercises
1. [Indenting your code to make it more readable](indentation) [*[download the starter code](indentation.zip)*]
2. [Fixing Code with an HTML Validator](html_validator) [*[download the starter code](html_validator.zip)*]

## Agenda
1. Hellos/Last week recap
    1. Taking attendance after class based on Zoom numbers
    1. In order to be marked on time, you must be in the Zoom waiting room by the class start time (12:30);
    1. If you miss over 30 minutes of class, you will be marked absent for the day.
    ---
    
1. What is HTML?
    1. Turn off CSS styling (View --> Page Style --> No Style)
    1. Open a web page and view source (https://crouton.net)
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
        1. headers:
            1. &lt;h1&gt;
            1. &lt;h2&gt;
            1. &lt;h3&gt;
            1. &lt;h4&gt;
            1. &lt;h5&gt;
            1. &lt;h6&gt;
        1. paragraph: &lt;p&gt;
        1. anchor (link): &lt;a&gt;
        1. &lt;div&gt;
        1. &lt;span&gt;
        1. &lt;header&gt;
        1. &lt;main&gt;
        1. &lt;footer&gt;
        1. &lt;nav&gt;
        1. &lt;section&gt;
        1. Lists:
            1. unordered list: &lt;ul&gt;
            1. ordered list: &lt;ol&gt;
            1. list item: &lt;li&gt;
        1. &lt;img&gt;
    1. HTML Attributes (things that go in the opening tab of an element, and are specific to that element)
        1. href (e.g. &lt;a href="https://crouton.net"&gt;)
        1. src (e.g. &lt;img src="https://picsum.photos/100&gt;)
        1. alt (e.g e.g. &lt;img src="https://picsum.photos/100&gt; alt="A cloudy forest with, mountain in the background)
        1. target (e.g. (e.g. &lt;a href="https://crouton.net" target="_blank"&gt;))
1. Go over good coding habits
    1. Comments
    1. Proper indentation:
        1. **In-class exercise** Complete the [Proper indentation exercise](indentation) by correctly indenting the elements in the code [*[download the starter code](indentation.zip)*]
    ---

1. How to troubleshoot (do these steps in this order) More information in the [How to Troubleshoot Guide](../guides/troubleshooting)
    1. Make sure your code is properly indented
    1. Look through your code to spot any errors
    1. Run your code through an HTML validator and correct any errors
    1. If you're still having issues, try googling the problem you're having
    1. If you're still having issues, reach out to a friend, a peer, a tutor, or me with your issue. Use the [Troubleshooting Guide](../guides/troubleshooting) to make sure you're asking questions in a way that best helps others to help you!
    1. **In-class exercise:** [Fixing Code with an HTML Validator](html_validator) [*[download the starter code](html_validator.zip)*]
1. Semantic HTML and Accessibility
    1. Semantic HTML vs. Decorative HTML
    1. Making accessible web pages is incredibly important. Throughout the semester, we will discuss design approaches that work well for everyone.
    1. Using semantic HTML is incredibly important for making accessible web pages
    1. Screen readers
        1. https://www.youtube.com/watch?v=dEbl5jvLKGQ
    ---
    
1. Making your first web page!
    1. **In-class Exercise:** Invent a recipe for a made-up dish. Create a web page for that recipe that includes the following:
        1. A title
        1. An image
        1. A corny backstory
        1. An ingredients list
        1. A list of instructions

        Make sure to use semantic HTML (meaning, you should use the elements that make the most sense for each section!). You should create the following page in a fresh Codepen called *HTML Recipe*
    ---
1. Discuss homework and where to find resources on Canvas
    1. HTML Basics Assignment: Creating a web page for a made-up business
    1. [Troubleshooting Guide](../guides/troubleshooting)

