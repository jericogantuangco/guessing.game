# A simple guessing game implemented with Go

This game is a simple guessing game that fulfills these requirements:

1. Generate a random number from 1 to 100, and store it as a target number for the player to guess

2. Prompt the player to guess what the target number is, and store their response.

3. If the player's guess is less than the target number, say, "Oops. Your guess was LOW."
   If the player's guess is greater than the target number, say, "Oops. Your guess was HIGH."

4. Allow the player to guess up to 10 times. Before each guess, let them know how many guesses the have left.

5. If the player's guess is equal to the target number, tell them, "Good job! You guessed it!" Then stop asking 
   for new guesses.

6. If the player ran out of tuns without guessing correctly, say, "Sorry. You didn't guess my number. It was: [target]."