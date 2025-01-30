
```markdown
# Snake Game

A classic Snake game implementation using HTML5 Canvas, CSS, and JavaScript.

![Snake Game Screenshot](https://via.placeholder.com/400x250.png?text=Snake+Game+Screenshot) 
*(Consider adding an actual screenshot later)*

**Live Demo:** [Play Now](https://wonderful-kitten-15a771.netlify.app/)

## Features

- Traditional snake game mechanics
- Responsive controls using arrow keys
- Score tracking with increasing difficulty
- Collision detection (walls and self)
- Food spawning system
- Game over detection and restart functionality
- Modern UI with clean styling
- Progressive speed increase as score improves

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/abhishektripathi-dev/snake-game.gti
   ```
2. Open `index.html` in a web browser

**OR**

Play directly online: [Live Demo](https://wonderful-kitten-15a771.netlify.app/)

## How to Play

- Use **arrow keys** (↑ ↓ ← →) to control the snake's direction
- Collect yellow food blocks to grow and increase score
- Avoid hitting walls or the snake's own body
- Game speed increases progressively with higher scores
- Click "Start Game" to begin or restart after game over

## Customization

You can modify various game parameters in the code:

```javascript
// Game settings
const gridSize = 20;          // Change grid cell size
let gameSpeed = 100;          // Initial game speed (ms)
const scoreIncrement = 10;    // Points per food collected
```

## Code Structure

### HTML
- Canvas element for game rendering
- Score display panel
- Start/Restart button

### CSS
- Modern dark theme styling
- Responsive layout
- Game container with shadow effects

### JavaScript
- Game loop management
- Snake movement logic
- Collision detection
- Food spawning system
- Score tracking and display
- Event listeners for controls

Main functions:
- `initGame()`: Initializes game state
- `spawnFood()`: Generates new food position
- `moveSnake()`: Handles snake movement and collisions
- `drawGame()`: Renders game elements
- `gameLoop()`: Main game loop controller

## License

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Connect with the Creator

**Abhishek Tripathi**  
- 🔗 LinkedIn: [https://www.linkedin.com/in/imabhishek-tripathi/](https://www.linkedin.com/in/imabhishek-tripathi/)
- 🐦 X (Twitter): [https://x.com/imabhishek_tri](https://x.com/imabhishek_tri)
- 🐙 GitHub: [https://github.com/abhishektripathi-dev/](https://github.com/abhishektripathi-dev/)
- 📧 Email: [abhishektripathi3196@gmail.com](mailto:abhishektripathi3196@gmail.com)

## Acknowledgments

- Inspired by classic Nokia Snake game
- Modern JavaScript implementation
- Free to use and modify under MIT License
```
