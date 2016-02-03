# Tic Tac Toe Lab

**Objective:** Build a tic tac toe game in HTML and pure JavaScript.

This week we have been learning about writing functions, working with
loops, and writing conditionals. We also learned about how parts of
HTML work and function.

Today we will be making a Tic Tac Toe game using all of this.

## Minimum Requirements
* A user should be able to click on different squares to make a move.
* Every click will alternate between marking an `X` and `O`.
* Upon marking of an individual cell, use JavaScript to add a class to
  each cell to display separate colors.
* A cell should not be able to be replayed once marked.
* Add a reset button that will clear the contents of the board.

## How to get started
1. Construct a `index.html` to be your starting point on this
   project. Add your necessary HTML tags, including `script` and
   `link` tags to link to your JavaScript and CSS respectively.
2. Before you even start working with JavaScript, construct the
   gameboard. The gameboard page should include the 3x3 grid, and at
   minimum a reset button. Using `id` and `class` on clickable
   elements will help you wire this up in JavaScript afterwards.
3. JavaScript portion will be next:
	* Locate the element first to use it within your app. Think about
      using `document.getElementById` or
      `document.getElementsByClassName` to locate your target
      elements. Try this in your console to make sure your selection
      works.
	* After finding the elements, start writing logic to listen for
      `click` events on those elements.
	* You will also need a variable to keep track of moves. As this
      will be used to indicate whether or not to draw an `X` or an `O`.

## Bonus
* Display a message to indicate which turn is about to be played.
* After the necessary moves have been played, stop game and alert the
  winner if one player ends up winning with three in a row.
    * Hint: Determine a set of winning combinations. Check those
      combinations on the board contents after every move.

## Ultra Bonus
* We once had a student implement an Artifical Intelligence (AI)
  opponent. If you really need a challenge, write some code that will
  play a game of Tic Tac Toe against you. (Hint: look into the minimax
  algorithm).
