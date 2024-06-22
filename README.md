# WaterPuzzle-main
WaterPuzzle-main

Project Overview
my project is a web-based clone of the popular "Water Sort Puzzle" game. The game involves sorting different colored liquids into separate glasses (test tubes) so that each glass contains only one color. You've built this game using HTML, CSS, and JavaScript.
File Structure
1.	HTML: Defines the structure and content of the web page.
2.	CSS: Provides the styling to make the game visually appealing.
3.	JavaScript: Contains the game logic and interactivity.
HTML Structure
The HTML file (index.html) sets up the basic structure of the game interface. Here's a detailed breakdown:
1.	Doctype and Head Section:
o	The <!DOCTYPE html> declaration defines the document type.
o	The <head> section includes the title of the page and links to the CSS stylesheet.
2.	Body Section:
o	The <body> contains the main elements of the game:
	Game Container (<div id="game">): This div wraps the entire game.
	Menu (<div id="menu">): This section displays the different difficulty levels and a button to view the rules.
	Menu Heading: <div id="menu-heading">WATER SORT PUZZLE</div>
	Difficulty Levels: Divs with class lvl and unique ids for each difficulty level. Each has an onclick attribute that calls the OpenLevel() function with the corresponding difficulty level as an argument.
	Rules Button: A button to show the rules of the game, calling ShowRules() on click.
	Level Container (<div id="level">): This div will display the current level of the game.
	Rules Page (<div id="rules-page">): Contains the rules of the game, with a back button to hide the rules.
3.	JavaScript Inclusion:
o	The <script src="js/index.js"></script> tag includes the JavaScript file which contains the game logic.
CSS Styling
Your CSS file (css/style.css) will define the styles for the game elements, such as colors, fonts, layouts, and any animations or transitions. This makes the game look attractive and enhances user experience.
JavaScript Logic
The JavaScript file (js/index.js) is where the game functionality is implemented. Here are some key functions you might have:
•	OpenLevel(level): This function initializes the game for the selected difficulty level. It will likely set up the initial state of the game, including the number of glasses and the colors of the liquids.
•	ShowRules(): This function displays the rules page.
•	HideRules(): This function hides the rules page.
•	Game Logic Functions: Functions to handle the core game mechanics, such as selecting glasses, pouring liquids, checking win conditions, and restarting the game.
How to Start the Game
1.	Open the Project: Load the index.html file in a web browser. This will display the main menu of the game.
2.	Choose a Difficulty Level: Click on one of the difficulty level buttons (EASY, MEDIUM, HARD, VERY HARD, IMPOSSIBLE). This will call the OpenLevel() function with the corresponding difficulty level.
3.	Read the Rules: If you're new to the game, click on the "RULES" button to read the game instructions. Click "BACK" to return to the main menu.
4.	Play the Game: Once a level is loaded, start sorting the liquids by clicking on the glasses to transfer liquid according to the rules described.
5.	Restart if Needed: If you need to restart the level, there should be an option (not shown in the HTML snippet) to reset the game state.
Points to Consider
•	User Interaction: Make sure that the game correctly handles user inputs, such as selecting and deselecting glasses.
•	Game State Management: Ensure that the game state (the arrangement of liquids in glasses) is correctly maintained and updated after each move.
•	Win Condition: Implement a check to determine when the player has successfully sorted all liquids.
•	Responsive Design: Ensure the game interface is responsive and works well on different devices and screen sizes.
Deployment to GitHub
To deploy your project to GitHub:
1.	Initialize Git: In your project directory, run git init.
2.	Add Files: Add your files to the repository with git add ..
3.	Commit Changes: Commit your changes with git commit -m "Initial commit".
4.	Create a Repository on GitHub: Go to GitHub and create a new repository.
5.	Push to GitHub: Link your local repository to the GitHub repository and push your changes:
bash
Copy code
git remote add origin  https://github.com/rajdvasi98/WaterPuzzle-main
git branch -M main
git push -u origin main
Conclusion
Your project is a fun and engaging way to practice HTML, CSS, and JavaScript. By following this explanation, you can ensure your game is well-structured, user-friendly, and ready for others to play and enjoy. Good luck with your project!

