# Wordle Clone

A browser-based implementation of the popular word-guessing game Wordle. Test your vocabulary and deduction skills by trying to guess a 5-letter word in 6 attempts or less!

## Features

- Interactive keyboard interface
- Visual feedback for letter correctness
- 6 attempts to guess the word
- Built-in word dictionary
- Responsive design
- Animated tile flips

## How to Play

1. The game selects a random 5-letter word
2. Type your guess using the on-screen keyboard or your physical keyboard
3. Press Enter to submit your guess
4. The tiles will change color to show how close your guess was:
   - Green: Letter is correct and in the right position
   - Yellow: Letter is in the word but in the wrong position
   - Gray: Letter is not in the word
5. Keep guessing until you find the word or run out of attempts

## Technical Details

### Built With
- HTML5
- CSS3
- Vanilla JavaScript

### Game Configuration
- Word length: 5 letters
- Maximum attempts: 6
- Word dictionary: 50+ common English words

### Features Implementation
- DOM manipulation for dynamic board creation
- Event listeners for keyboard input
- CSS animations for tile flips
- Responsive layout using CSS Grid and Flexbox

## Getting Started

1. Clone or download the repository
2. Open `index.html` in a modern web browser
3. Start playing!

No additional setup or dependencies required - the game runs entirely in the browser.

## Browser Compatibility

The game works best in modern browsers that support:
- CSS Grid
- CSS Flexbox
- ES6 JavaScript features