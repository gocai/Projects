# Wordle-and-Wordle-Solver
At each turn, the player guesses a word, which must come from a shared list of
5-letter English words. There is a dictionary of 5-letter words embedded in the
code for the game. Then the game compares the player's guess to the true secret
word, and returns a *response*, where the response consists of 5 colored
squares.

The squares have the following meaning:
  * gray: the corresponding letter does not appear in the secret word
  * yellow: the corresponding letter appears in the secret word, but not in that
    corresponding slot
  * green: the corresponding letter appears in the secret word, in that slot.
To execute the code, in a terminal input the following : 
