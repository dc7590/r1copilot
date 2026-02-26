# 🍎 Fruit Memory Game 🍌

A simple and fun memory matching game built with HTML, CSS, and JavaScript featuring fruit symbols and sound effects!

## Features

- **4x4 Grid**: 16 cards with 8 pairs of fruit symbols to match
- **Fruit Symbols**: 🍎 🍌 🍇 🍊 🍓 🍉 🍑 🥝
- **Sound Effects**: Interactive audio for card flips, matches, mismatches, and victory
- **Sound Toggle**: On/off control for sound effects with visual feedback
- **Score Tracking**: Move counter and match counter
- **Responsive Design**: Works on desktop and mobile devices
- **Beautiful UI**: Gradient backgrounds and smooth animations

## How to Play

1. Open `index.html` in your web browser
2. Click on any card to flip it and reveal the fruit
3. Click on another card to find its match
4. If the fruits match, they stay revealed with a green background
5. If they don't match, they flip back after 1 second
6. Continue until all pairs are matched
7. Try to complete the game in as few moves as possible!

## Controls

- **🔊/🔇 Sound Button**: Toggle sound effects on/off
- **🔄 Reset Button**: Start a new game with reshuffled cards

## Running the Game

Simply open the `index.html` file in any modern web browser:

```bash
# Option 1: Open directly
open index.html  # macOS
start index.html # Windows
xdg-open index.html # Linux

# Option 2: Use a local server
python3 -m http.server 8000
# Then visit http://localhost:8000
```

## Technologies Used

- **HTML5**: Structure
- **CSS3**: Styling, animations, and responsive design
- **JavaScript**: Game logic and interactivity
- **Web Audio API**: Sound effects

## Game Rules

- Each turn, flip two cards
- If they match, they stay revealed
- If they don't match, they flip back
- Game ends when all pairs are found
- Each pair flip counts as one move

Enjoy playing! 🎮
