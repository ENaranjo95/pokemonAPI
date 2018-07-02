# My Pokemon Simple Server
This project is a node-js server that includes an api of my favorite Pokemon. Use can select a pokemon from the selector and display a description of the pokemon.

## How It's Made:
**Tech used:** HTML, CSS, JavaScript and Node-JS

The index.html contains a heading of the application, a select tag for the different pokemons available on the API, a search button and another heading with 2 span tags for the description of the pokemon. The main.js contains the function that runs when the user clicks on the search button. The function pulls on the value of the select tag and pass it as a parameter to the server.js api. The server.js takes the parameter and displays the appropriate information to the main.js as a JSON. The main.js then takes the JSON information and parses the information we need to display the description of the pokemon on the DOM.

## Optimizations
Some major changes I want to make is include more description of the  pokemon on our API and include more pokemons on the API. As we increase our database of Pokemon, change the select tag to an input tag and include a autofill feature to avoid spell errors. Also work on styling.


## Lessons Learned:
To come later after making changes.
