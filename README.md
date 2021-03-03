# javascript-dice-set
Exercise using JS 

This is a game for two players.
Each player will use a 6 sided dice (1d6)
Refreshing the page will provide each player a value in range 1-6 [note: range(1,7) for programmers]
The value generated will be displayed using the corresponding image of the side of the dice. 
The player with the highest value wins. This will be shown in the title [h1 element]
If both players yield the same value, it will be a drwan
Refresh the page for playing again


This exercise is about:
-Understanding the DOM
-Creating variables
-Select and manipulate elements on the fly:
  The h1 element will change depending of the player who won.
  if statements (control flow) will change the behavior of our page depending on the circumstances.
-Generating random numbers 
  Math.random() does not provide cryptographically secure random numbers.
  Concatenating JS strings to diplay the correspondig img
