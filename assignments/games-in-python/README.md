
# 📘 Assignment: Games in Python

## 🎯 Objective

Build the classic Hangman game using Python to practice string manipulation, loops, conditionals, and user input handling.

## Learning Objectives

After completing this assignment, you will be able to:
- Use strings and lists to manage game state
- Implement loops and conditionals for game logic
- Handle user input and validate player guesses
- Use Python's `random` module for selection

## 📝 Tasks

### 🛠️ Task 1: Set Up the Game

#### Description
Create the foundation of your Hangman game with word selection and game initialization.

#### Requirements
Your program should:
- Import the `random` module
- Define a list of at least 10 words to guess
- Randomly select one word at the start of each game
- Initialize variables for tracking game state (guesses, attempts remaining)

### 🛠️ Task 2: Display Game State

#### Description
Show players the current game progress and how many attempts they have left.

#### Requirements
Your display should:
- Show the word with guessed letters revealed and remaining letters as underscores (e.g., `_ _ L L O`)
- Display list of letters already guessed
- Show number of incorrect guesses remaining
- Be clear and easy to read

### 🛠️ Task 3: Accept and Process Guesses

#### Description
Handle player input and update the game state based on their guesses.

#### Requirements
Your program should:
- Prompt player for a single letter guess
- Validate that input is a single letter (handle invalid input gracefully)
- Check if letter is in the word
- Update the guessed letters list
- Decrease attempts if guess is incorrect
- Prevent duplicate guesses (if desired)

### 🛠️ Task 4: Win/Lose Conditions

#### Description
Determine when the game ends and display appropriate messages.

#### Requirements
Your program should:
- End game when word is completely guessed (win)
- End game when attempts reach zero (lose)
- Display the hidden word and outcome message
- Ask player if they want to play again

## 🚀 Getting Started

1. Open `starter-code.py` to see the template with helpful comments
2. Follow the TODO comments in the code
3. Test your game with different words and guesses
4. Make sure your game handles edge cases (duplicate guesses, non-letter input, etc.)

## 💡 Tips & Resources

- Use `in` keyword to check if a letter is in the word
- Use `set()` to track guessed letters efficiently
- Test with a friend to make sure the game is fun and works correctly!

## ✅ Submission Checklist

Before submitting, ensure:
- [ ] Your game runs without errors
- [ ] All four tasks are completed
- [ ] Player can win and lose properly
- [ ] Invalid input is handled gracefully
- [ ] Code includes helpful comments
