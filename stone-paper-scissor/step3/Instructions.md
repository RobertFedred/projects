In this step, We will make functionality for the result screen and User/Computer score.

When the computer makes it choice depending on the choice change the inner HTML of the result screen.

To achieve this functionality
first access the result screen by 

``text
let resScreen = document.getElementById('result-screen')
```
( Here Id is the id of the result screen )

resScreen.innerHTML = (Your emoji/Text)

You can use an emoji like this 🤖 which you can use as default. (To show Before/After the computer makes choice)

In the same way access the User/Computer Score screen.
Depending on the winner increase the score by +1.

You may also prompt for Number of plays while initializing the game so that the number of plays are limited other wise it will be
never ending game.

Add a counter inside the result() function so that whenever the counter gets equal to the Number of plays the game should end.