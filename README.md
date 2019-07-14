# word-guess-game
HW 3: Who's That Pokemon?

1.Create a new GitHub repo Word Guess Game. Then, clone it to your computer. 

-Inside your local git repository, create an index.html. 
  -While still in your local git repo, create a directory called assets. 
  -cd your way into the assets folder, then make three additional folders: javascript, css and images.

In the javascript folder, make a file called game.js. -Use the src attribute of the script tag to link to this file, rather than embedding the code directly in your HTML document.

In the css folder, make a file called style.css. -Also in the css folder, make a file called reset.css. Paste into it the code from the Meyerweb reset stylesheet. If you opt to use Bootstrap instead of writing your own CSS, skip this step, and simply include a link to Bootstrap via CDN.

4.In the images folder, save whatever images you plan on using.

What your file organization should look like. ├── assets | ├── css | | └── style.css | ├── images | └── javascript | └── game.js └── index.html

Push the above changes to GitHub.

GAME NOTES:

1. Choose a theme for your game! In the demo, we picked an 80s theme: 80s questions, 80s sound and an 80s aesthetic. You can choose any subject for your theme, though, so be creative!
2. Use key events to listen for the letters that your players will type.
3. Display the following on the page:
  -Press any key to get started!
  -Wins: (# of times user guessed the word correctly).

ex: If the word is madonna, display it like this when the game starts: _ _ _ _ _ _ _.
    As the user guesses the correct letters, reveal them: m a d o _  _ a.

  -Number of Guesses Remaining: (# of guesses remaining for the user).
  -Letters Already Guessed: (Letters the user has guessed, displayed like L Z Y H).
  -After the user wins/loses the game should automatically choose another word and make the user play it.
