2048 Game is an implementation of the popular logic game 2048, created using pure JavaScript, SCSS, and HTML. Players can move tiles with numbers on a square grid, merging tiles with the same values ​​to reach the tile with the number 2048. The game offers an intuitive interface and engaging gameplay, allowing players to develop their strategic skills.

Main features:

Moving tiles in four directions (up, down, left, right).
Merging tiles with the same values.
Generating new tiles after each move.
Displaying the current score and whether the 2048 tile has been reached.
Ability to reset the game and start over.
Technologies used
HTML: Used to create the structure and layout of the game interface. HTML elements provide the basis for displaying tiles, buttons, and score information.


SCSS: is a CSS preprocessor that was used to style the game. SCSS allows for variables, nested rules, and mixins, making creating and maintaining styles easy. The game design includes attractive colors, animations, and a responsive interface.

JavaScript: The main programming language used to implement the game logic. JavaScript handles the movement of tiles, combining values, generating new tiles, and handling user input. The code is written using pure JavaScript, which ensures high performance and ease of understanding.

https://alexliashenko19.github.io/2048-Game/

Run git clone first, you need to clone the repository to your local machine.

Run node -v make sure you have Node.js installed on your machine.

Run nvm install 16 it is recommended to use Node.js version 14.x or 16.x for compatibility with the dependencies in this project.

Run npm install to install the dependencies

Run npm start to run a development server at http://localhost:3000 (If you need to stop the server press ctrl + c in the terminal window) Open one more terminal and run tests with npm test to ensure your solutions are correct

Run npm run lint to check the code style and fix all the errors

Run npm run build if you want to create a production build of your application

Run npm run deploy if you want to deploy your application to GitHub Pages
