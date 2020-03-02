# comm645Final
Final Assignment for COMM645 in FEWD2

## Build a Responsive Website
Build a 3 page (minimum) responsive website, using the principles discussed thus far. 

This responsive website should include the following features:

* A responsive website should include a grid system (flex and/or grid), media queries, and images that resize.
  * All code should be custom coded.
  * The grid system can have as many or as few columns as you require.
  * You should include at least two media queries in your CSS. You may have more than this if you require it.
  * The images need to resize in a responsive way, keep in mind file size when optimizing your images and deciding which ones you should use for large and small screens. 
  * The site should include a navigation bar that links the relevant pages together, and it should be available on all pages of the site. Your navigation should be responsive.
* **If you need images for your site**, you can find many free image websites online. I like http://www.freeimages.com/ but there are many others. Remember that only .jpg, .png, and .gif images work on the web, and remember that you should resize your images to optimize download time. 
* You will need to upload your project to GitHub and submit your repo address for me to access so I can grade your project.

## In regards to SASS
* When compiling your Sass, make sure the output is **expanded**, not nested, compact, or compressed.
* Make good use of variables, mixins, extend, nesting, math, built-in functions, etc.
  * Use **comments** to identify the various necessary components in your sass files. Include one necessary comment, and at least one hidden comment (you may want to use multiples of either of these).
  * Utilize a **math operator**. Comment the section where you use a math operator.
  * **Modify colors** using a SASS color function. Get creative and try to do something that is not possible with straight CSS. Comment the section where colors are modified.
  * Use **variables** whenever values are repeated. Comment the section where variables are stored.
  * Use one of the **list properties** to modify and customize your code. Comment out where this code is being used. 
  * Incorporate a **map** into your code, show that you understand how to use this in your code. Create a comment that shows where this code is found.
  * Review the sass documentation under ['flow content'](https://sass-lang.com/documentation/at-rules/control), add an **@for**, **@each** or **@while** command (pick one that is most appropriate for your website).
  * Create at least 1 custom-coded **mixin**. Comment the section where mixins are stored.
  * Demonstrate proper use of **extend** in at least 1 instance. This can extend an existing style or an extend-only class. Place a comment where the extend exists.
  * Demonstrate **nesting** to 2 levels in at least one instance. Comment the area where nesting exists.
  * Incorporate at least 2 instances of **built-in Sass functions**. You may use functions covered in class or any of the functions listed at the Sass website: http://sass-lang.com/documentation/Sass/Script/Functions.html. Comment where you’ve used a Sass function.
  * Demonstrate the use of **if/else** in at least one instance. Comment your instance of if/else.
  * Use at least 2 partial files in managing your Sass.
* Your SASS should be **super dry and well-structured**: making use of variables that link together to control the overall size of the document (i.e. hooking together a base font size with other font sizes, padding, margins, etc), interesting mixin choices that you code.
* Create both unminified and minified versions of CSS.

## What I care about
* **You create a grid system that makes sense with your design.** It doesn’t have to be complicated, messy, or long to do well. Simple is fine.
* Your Sass is DRY and well-formed.
* You add comments next to the necessary items specified above
* You can demonstrate that you understand how to use SASS and that you can take advantage of what it has to offer in regards to enhancing and simplifying your work. 
* HTML and CSS validate (always).

## How to turn in your assignment
Turn your assignment in via the Assignments link in Canvas.

Include a Canvas comment in your submission, indicating the following:

* **Paste the URL for the assignment GitHub in the comment.** 
* **In addition, zip up your entire root folder and upload these to canvas as well.**
* Indicate which partial files and starting line numbers the following requirements are located on:
  * Variables section
  * Math Operator
  * Color modifier
  * List properties
  * Map
  * 'Flow Content' item
  * Custom mixin
  * Extend
  * Nesting
  * Built-in Sass functions
  * If/else
