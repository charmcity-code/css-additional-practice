# CSS-Extra-Practice

Before getting started:
_Please review the documentation provided on the CSS box model_

1. https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/The_box_model
2. https://www.w3schools.com/css/css_boxmodel.asp

## This practice will walk you through various CSS implementations.

_Exercise one: Compose valid element-level CSS in an HTML file_

Element-level CSS refers to the utilization of CSS directly on the object the style is being applied to.

_Here is the checklist for this portion of the demo:_

    1. Change the color of the h1 element to be red

    2. Change the position of the h1 element to be centered

    3. Change the color of the h2 element to be green

    4. Change the position of the h2 tag to be centered

    5. Create a container for the game

    6. Center the game container

    7. Create a grid of 9 boxes 3 across(you can use spans for this)

    8. Create black boarders on each box

    9. Round the corners on all boxes(review border-radius documentation)

    10. Add an X or O to each box to simulate a game of tic tac toe.

    11.	Change the boarders of the winning three boxes to red

    12.	Add a text field below the game to indicate the winner of the simulated game.

    13.	Save your changes to the exercise1 html file

---

_Exercise two: Compose valid CSS in an HTML file's style tag in the head_

CSS utilizes selectors to identify a specific object or category of objects to apply styling to. These selectors include tag, class, id and class. For this exercise we are going to use certain selectors to change the CSS of the elements in our demo page.
The advantage of a style component over element level styling is that rules can be applied to multiple elements while being defined once. With element level styling it is necessary to add CSS to each element individually which can be advantageous in some situations but is generally not considered best practice.

_Here is the checklist for this portion of the demo:_

    1. Copy your code from exercise 1 into exercise 2

    2. Create a style element within the head of the exercise 2 html file to handle CSS

    3. Move the element level CSS to the Style element

    4. Move on when the page styling achieved in exercise 1 is now represented  using a style element

---

_Exercise three: Compose valid CSS in an external CSS file, and include it via a link tag_

While using a style element to keep all styling rules in a single location as the number of rules increases this element will also increase. For cleanliness of code and readability it is better to keep CSS in a separate file and link to it in the html file.

_Here is the checklist for this portion of the demo:_

    1. Copy your code from exercise 2 into exercise 3

    2. Create a style.css file in the demo

    3. Move CSS from the style element to the style.css file

    4. Link to the style.css file in the html file

    5. Move on when the page styling achieved in exercise 1 and 2 is now reflected in exercise 3 using a linked css file
