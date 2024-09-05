
This is a classic Hangman game implemented in Python, using the `graphics.py` library to display the hangman drawing. Players attempt to guess the correct word by inputting letters, with each incorrect guess leading to the drawing of the hangman.

How to Play:
1. Run the game by executing the Python script.
2. A word is randomly chosen from a predefined list, and your goal is to guess the word letter by letter.
3. For every incorrect guess, a part of the hangman is drawn.
4. You win by guessing the word correctly before the hangman is fully drawn (7 incorrect guesses).
5. You can play multiple rounds by selecting "y" when prompted to play again.

Features:
- Random Word Selection: A new word is chosen at random for each game from a large word list.
- Interactive Graphics: A graphical window is displayed, showing the hangman as it's progressively drawn with each incorrect guess.
- User Input Validation: Ensures that only single alphabetic characters are accepted as valid guesses.
- Multiple Rounds: After completing a game, you are given the option to play again.

Setup Instructions:
1. Clone the Repository: Clone or download the repository to your local machine.
2. Install the `graphics.py` library: Ensure that `graphics.py` is in the same directory as your project or installed in your Python environment.
3. Run the Game: Open a terminal or command prompt, navigate to the project directory, and run the game.
   
Gameplay Instructions:
- After launching the game, the program will display an empty word represented by underscores.
- You will be prompted to guess a letter.
- Correct guesses reveal the letter's position in the word, while incorrect guesses draw a part of the hangman.
- Continue guessing until the word is complete or the hangman is fully drawn.
- Play again: After each game, you can choose to play again by typing "y" or exit by typing "n".

The game randomly selects words from a diverse list of over 250 words, ranging from common to more challenging vocabulary.

Enjoy playing the Hangman Game!
