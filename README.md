# bagels
The bagels game where a 3-digit random number has to be guessed given several clues.

Instruction to run the game: Clone or download, compile both .java files and run using the BaglesTest.java file.

Here are the rules of the game:

The computer will generate a "secret" three digit number at random. The first number will not be 0, and all the digits will be different.  The user tries to guess the number.  If the user guesses correctly, then the game is over.

If not, the computer gives a hint and the player tries again. 

The hints:
•	for each digit that matches the secret number in the proper place, the computer prints "Fermi".
•	for each digit that matches, but not in the proper place, the computer prints "Pico".
•	if none of the digits match, the computer prints "Bagels".

Examples (supposing that the secret number is 482):

		guess = 637, Bagels
		guess = 381, Fermi
		guess = 382, Fermi Fermi
		guess = 832, Fermi Pico
		guess = 328, Pico Pico
		guess = 428, Fermi Pico Pico
		guess = 482, Winner! (the game is over)

When the game is over, the results are printed: whether the user won or quit, and the number of guesses made.
