# JavaScript Simon Game

A browser-based implementation of the classic Simon memory game built using vanilla JavaScript. The application challenges users to remember and reproduce increasingly complex sequences of colors and sounds, demonstrating core front-end development concepts such as DOM manipulation, event handling, and game state management.

## Badges

![Repo Size](https://img.shields.io/github/repo-size/drussell33/JavaScript-Simon-Game)
![Last Commit](https://img.shields.io/github/last-commit/drussell33/JavaScript-Simon-Game)
![Top Language](https://img.shields.io/github/languages/top/drussell33/JavaScript-Simon-Game)

## Key Features

- Interactive Simon game with color sequence memory challenge
- Dynamic sequence generation that increases in difficulty
- User input handling via button clicks
- Visual and audio feedback for each step in the sequence
- Game over detection with restart capability
- Real-time comparison of user input against generated sequence

## Tech Stack

### Frontend
- HTML
- CSS
- JavaScript (Vanilla)

### Backend
- None

### Database
- None

### Tools / Services
- Web Browser (for execution)

## Architecture Overview

This project is a client-side web application with no backend or database dependencies. The architecture is centered around:

- **Game State Management**: JavaScript maintains arrays for the generated sequence and user input.
- **Event Handling**: Button click events trigger user input and validation logic.
- **DOM Manipulation**: Visual updates (button highlights, animations, messages) are applied dynamically.
- **Control Flow Logic**: The game loop progresses through levels, validates input, and handles game-over conditions.

The application follows a simple procedural approach with modular functions responsible for sequence generation, input validation, and UI updates.

## Project Structure

```bash
JavaScript-Simon-Game/
├── index.html        # Main HTML structure
├── styles.css       # Styling for layout and game elements
├── script.js        # Core game logic and interactions
└── README.md        # Project documentation
```

## Getting Started

### Prerequisites

- Modern web browser (Chrome, Edge, Firefox, Safari)

### Installation

```bash
git clone https://github.com/drussell33/JavaScript-Simon-Game.git
cd JavaScript-Simon-Game
```

### Usage

Open the application in your browser:

```bash
open index.html
```

Or double-click the `index.html` file.

## Roadmap

- [x] Basic game functionality
- [x] Sequence generation logic
- [x] User input validation
- [x] Visual feedback for button presses
- [x] Game over handling
- [ ] Add sound effects (if not already implemented)
- [ ] Improve UI/UX styling
- [ ] Add mobile responsiveness
- [ ] Add high score tracking
- [ ] Add difficulty modes

## Contributing

Contributions are welcome. To contribute:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/new-feature`)
3. Commit your changes (`git commit -m "Add new feature"`)
4. Push to your branch (`git push origin feature/new-feature`)
5. Open a Pull Request

## Screenshots / Demo

_Add screenshots or a live demo link here._

## Contact

- GitHub: https://github.com/drussell33
