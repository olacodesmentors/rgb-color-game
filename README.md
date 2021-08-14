# The RGB Color Game

## Pre-requisite

This task assume that you already understood the following:

- Basic HTML
- Basic CSS
- Fundamentals Javascript Syntax
- DOM manipulation

***Note: If you do not have any previous knowledge of the above, Kindly revisit them.***

## For Context

Specifying an RGB color that fits the exact need is an arduous tasks and not easy to learn. In this project we want make RGB learning as easy and as fun as possible by creating an `RGB Color Game`.

RGB is an acronym that stands for Red Green Blue. The RGB color model is an additive color model in which the red, green, and blue primary colors of light are added together in various ways to reproduce a broad array of colors.

## The Game

RGB Color Game is an interactive game that will constant update the player

At the start of the Game, the

- Game should show an RGB function that the user will guess e.g rgb(255, 111, 10)
- show at least 6 boxes of random colors which includes the result of the RGB color to guess
- And a `New colors` button

The player can go with any of the following choice:
<!-- The flow -->

- The player can click on a `New color` button and it should re-generate a new random colors
- The player is expected to guess correctly the RGB color function shown to him
  - If the player guess the color correctly
    - A congratulatory message is shown to the user
    - All of other colors turns into the correct color
    - The `New colors` button change to `Play Again`,
    - Then the player can play again.
  - Else if the player guess was wrong
    - A failure message is shown to the user
    - The wrong color clicked should be removed from the screen increases the player chance of guessing right
    - The player can try again and click another color until he get it right

## Approach

1. Break down the project to chunks
2. Create small functions to handle specific tasks
3. Create a separate file for HTML, CSS and Javascript
4. Make sure you name your HTML file an `index.html`
