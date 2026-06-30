# Fumble Hero

**Fumble Hero** is a humorous, physics-based endless runner game where clumsy characters trip, stumble, and face-plant their way through increasingly difficult terrain. Tap to control the character's movements and try to survive as long as possible to set a new high score!

## Features

- **Chaotic Physics**: Experience unpredictable and hilarious movement mechanics as your hero stumbles around.
- **Endless Gameplay**: The game gets progressively harder the longer you survive.
- **Combo System**: Chain successful moves to build up your score multiplier.
- **High Score Tracking**: Compete against your best runs with local high score storage.
- **Responsive Design**: Optimized for both desktop and mobile devices.
- **Humorous Quotes**: Receive witty commentary upon each "game over."

## How to Run

Since this is a static web-based game, you can run it directly in any modern web browser.

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge).
- No server required, but running on a local server is recommended for best performance with Canvas APIs.

### Steps

1. **Clone or Download the Repository**
   Ensure you have all the necessary files (`index.html`, `style.css`, `script.js`, etc.) in a single directory.

2. **Open in Browser**
   - Simply double-click `index.html` to open it in your default browser.
   - *Alternatively*, use a local development server (e.g., VS Code Live Server) for a smoother experience:
     ```bash
     # If you have Python installed
     python -m http.server

     # Then open http://localhost:8000 in your browser
     ```

3. **Play!**
   - Click "PLAY" on the main menu.
   - Tap the screen (or click) to make your hero face-plant or jump, depending on the current obstacle.
   - Try to avoid falling off or hitting obstacles to increase your score.

## Project Structure

```
├── index.html      # Main HTML structure
├── style.css       # Styling for menus, canvas, and UI elements
├── script.js       # Game logic, physics engine, and rendering
└── README.md       # This file
```

## License

This project is open source and available under the [MIT License](LICENSE).

---

*Note: Ensure that all associated CSS and JavaScript files are present in the same directory as `index.html` for the game to function correctly.*