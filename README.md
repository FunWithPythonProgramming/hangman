The code in this repository will allow us to play a simple game of hangman.

Goal:
With the given list of words, we want to pick a random word and have the user guess what the word will be. The user can win if and only if they guess all the letters in the word before hitting the threshhold. We must fulfill the following requirements:

* Randomly select word from list
* Repeatedly ask user for input until word is solved or they have used up all their guesses
	* User Input must be validated (can only be a single letter)
* User must receive output each guess:
	* How many guesses are left
	* What letters have already been guessed
	* Current status of guessed word

