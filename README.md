# Key_presser_js
# Hosted Link:-https://tulasidurga1.github.io/Key_presser_js/
# Explanation:-
### Here's a breakdown of the code:

# HTML (index.html):
-The HTML structure is defined within <!DOCTYPE html> tags.<br>
-A <meta> tag sets the character encoding and viewport settings.<br>
-The page's title is set to "Key Presser."<br>
-A reference to an external stylesheet "style.css" is included.<br>
-The content of the page is within the <body> element, containing a <div> element with a class "container."<br>
-A <script> tag references an external JavaScript file "index.js."<br>
### JavaScript (index.js):
- An event listener is added to the document object, listening for the "keydown" event. This event fires when a key is pressed.
- Inside the event listener:-
- The container variable is selected, referring to the <div> element with the class "container."
- The innerText of the container is cleared to prepare it for new content.
- Information about the pressed key and its key code is displayed:<br>
-A new (header) element is created with text indicating the pressed key.<br>
-A new  (paragraph) element is created with text indicating the key code.<br>
-Both the h1 and p elements are appended as child elements to the container to display the information.<br>
 CSS (style.css):

### CSS is used to style the page.
-The * selector applies styles to all elements, setting margins, padding, and the box-sizing property.
-The .container class styles the div element:
-It uses flexbox to center its content both vertically and horizontally.
-It sets a specific font size and weight.
-Additional styles for <p> and <h1> elements are defined.
