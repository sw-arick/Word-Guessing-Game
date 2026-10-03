# Word Guessing Game

A command-line word guessing game written in Python. The game greets you by name, picks a random word, and you guess it one character at a time. You can make 12 wrong guesses before you lose.

## Features

- Personalized greeting using your name
- Random word picked from a built-in list on every run
- Hidden word shown as blanks that fill in as you guess correctly
- 12 turns, lost only on wrong guesses
- Input validation: guesses that aren't a single character, or that you've already made, don't cost a turn
- Win and lose messages that reveal the word

## How to play

1. Run the program and enter your name.
2. Guess one character at a time.
3. Correct characters appear in the word; wrong ones cost a turn.
4. Reveal the whole word before you run out of turns.

## Example

```
What is your name? Sam
Good luck! Sam

Guess the characters
_ _ _ _ _
Guess a character: a
_ _ _ _ _
Wrong
You have 11 more guesses
```

## Run it locally

```bash
git clone https://github.com/sw-arick/word-guessing-game.git
cd word-guessing-game
python main.py
```

Requires Python 3. No external libraries needed.

## Concepts used

- `random.choice()` for picking a word
- `while` loop for the game flow
- Strings to track guessed characters
- A counter to detect when the whole word is revealed
- `continue` to skip invalid or repeated input

## Ideas for improvement

- Add a "play again" option
- Add ASCII hangman art that changes with each wrong guess
- Load words from a text file
- Add difficulty levels with different turn counts
- Only accept letters as guesses

## Author

[sw-arick](https://github.com/sw-arick)
