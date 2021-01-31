# Troubleshooting Guide
### When we're coding, we usually spend more time debugging and fixing errors than we do actually coding, so it's incredibly important to be a diligent debugger! If your code isn't doing what you expect it to do, follow these steps in order:

## Obey the commandments of good coding practice!
1. NO SPACES in your filenames (dashes (-) and underscores (_) are fine!)
1. Use LOWERCASE names for all files and folders
1. Use SHORT names for your files and folders
1. Use MEANINGFUL names for your folders and media files
1. ORGANIZE your files into folders
1. INDENT your code properly
1. Use FIREFOX to test out your web pages
1. Use CONSISTENT file extensions. For example, if you have an *images* folder with two images; one is called 'fish.**jpg**' and the other is called 'cat.**jpeg**', make sure they are both using **.jpg** for their file extension.

## Solving your HTML and CSS problems

#### 1. Make sure your code is indented properly
If your code is hard to read, and it can be hard to find mistakes. Making sure your code is indented as you code can also help to prevent mistakes in the first place.

#### 2. Look over your quickly to find obvious errors
Once your code is indented, look over your code to see if you can spot any obvious errors, like if any of your code is red. If you can't spot an error after a quick skim of your code, use an HTML Validator.

#### 3. Use an HTML Validator to catch less obvious errors.
HTML validators are a great way to not only find errors in your code, but also to learn what the solutions are. Visit an HTML Validator like this one: https://validator.w3.org/#validate_by_input (or you can just Google 'HTML Validator' and one will come up)
##### Here's the process you should follow when working with the Validator:

1. Copy ALL of the code! (Hint: use the Select All Keyboard shortcut (Command + A (Mac), CTRL + A (Windows)))
1. Paste it into the Validator and press 'Check'
1. If you have any errors, read and understand the first error
1. Go back into your code and fix the first error
1. Repeat steps 1-5 until you have no more errors!

##### Some things to note:

* You should only fix one error at a time. Sometimes, fixing one error will reveal more errors that weren't mentioned the first you checked your code.
* Alternatively, sometimes fixing one line of code will actually fix multiple errors at once!
* Check your text editor (VS Code) for any red text
* Get comfortable with computer shortcuts to speed up the process:
    * Swap between applications: Command + Tab (Mac), ALT + Tab (Windows)
    * Select All: Command + A (Mac), CTRL + A (Windows)
    * Copy: Command + C (Mac), CTRL + C (Windows)
    * Paste: Command + V (Mac), CTRL + V (Windows)

If you've fixed all the errors in the validator, but your code still doesn't look how you expect it to, try the following...

#### Fix things like broken links

While Validators are really useful, they can only catch HTML or CSS mistakes; they won't notice if your page links or image links are wrong!

If an image, or video, or sound file, or link to another page isn't working, it's probably because you aren't linking to it correctly. Look at the **href** or **src** of an element to make sure it is being linked to correctly.

If you're still having issues...

#### Take a close look at your code, line by line
After doing all the other steps, you might still have some issues. Look at your code line by line and see if you can spot what the problem is. If, after doing this, you're *still* having problems, it's time to ask for help!

## How to ask for help
Having a second set of eyes on your code can be incredibly helpful. Even if we think we know how to solve a problem, sometimes we just can't see the issue since we've been coding for hours on end and our brains are fried. But often, we just don't know what to do, and need help!

In order to get the best help, help your helper help you! If you're asking for help over email or instant message, make sure to do the following.

#### 1. Clearly explain the issue you're having
This can be tricky; if we knew the issue, then we might not need help! Explaining the issue might even lead you to solving the problem yourself!

#### 2. If you can't explain the problem directly, describe what you're trying to achieve, and the things you tried doing
Saying "I'm trying to do X, but no matter what I try, I can't get it to work" is a good start, but it's extra helpful if you explain the things you attempted, so the person helping you doesn't spend time telling you to try something you've already tried.

#### 3. Include relevant screenshots and code in the email
You can include the following in the email:
1. screenshots of your code
1. the code files themselves
1. the error messages you're getting
1. a screenshot of your file explorer in VS Code (so the person helping can see how your files and folders are laid out. That's especially helpful if your issue has to do with broken links.)
1. all of the above.

#### 4. Include other relevant information
Make sure to mention what operating system or device you're using (e.g., a Windows Desktop, and iPhone, etc.)

## Important note:

If I receive an email asking for help, and it appears you haven't followed this guide first, I will happily (and passive-aggressively ;) ) respond to your email with nothing but a link to this guide.

Keep in mind, learning how to solve your own problems effectively is just as important as learning code itself. If I email just a link to this guide, and it comes off as flippant, or snarky, I promise that I'm doing it to help you be a better coder! Trust me, I genuinely *love* to work through coding bugs with you all; it's like solving a puzzle! But I want to help you with the trickier stuff, and not the stuff that I bet you could figure out if you just went back and looked for it :)