# Typing Speed Game

This is a fun and interactive typing speed game. The game measures your typing speed in words per minute (WPM) and characters per minute (CPM), tracks mistakes, and gives you 60 seconds to type as much as you can from a random paragraph.

## Features

- **Typing Speed Calculation**: Calculates Words Per Minute (WPM) and Characters Per Minute (CPM).
- **Mistake Counter**: Tracks the number of mistakes made during typing.
- **Random Paragraphs**: The game uses a variety of random paragraphs for testing typing speed.
- **Reset Functionality**: Users can restart the game with the "Try Again" button.
- **Timer**: Users have 60 seconds to complete the game.

## Project Structure

```bash
├── index.html       # Main HTML file
├── style.css        # CSS file for styling
└── js
    ├── paragraph.js # Array of random paragraphs for typing test
    └── script.js    # Logic for the game (timing, mistakes, etc.)
```

## How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/typing-speed-game.git
   ```

2. Navigate to the project directory:
   ```bash
   cd typing-speed-game
   ```

3. Open `index.html` in your web browser:
   - Right-click `index.html` and open it with your favorite browser.
   - Or, if you have a local web server, start the server and view the game.

## Game Instructions

1. Open the game in your browser.
2. A random paragraph will appear on the screen.
3. Start typing the paragraph in the input box. Your typing speed and mistakes will be calculated in real-time.
4. You have 60 seconds to type as many words as possible.
5. After the time is up, you can press "Try Again" to restart the game.

## Customization

You can customize the paragraphs used for the typing test by modifying the `paragraphs` array in the `js/paragraph.js` file. Feel free to add your own text!
