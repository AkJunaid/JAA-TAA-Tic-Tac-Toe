# JAA TAAA Tic-Tac-Toe

A modern, interactive Tic-Tac-Toe game featuring country battles with AI and two-player modes.



## Features

### Game Modes
- **Play vs AI** - Challenge the computer opponent with intelligent AI
- **Two Players** - Play locally with a friend on the same device

### Country Selection
Choose from 7 different countries to represent you in battle:
- Bangladesh
- China
- India
- North Korea
- Russia
- USA
- and a Dick

### Unique Mechanics
- **Random Opponent** - Let the game randomly select an opponent country when playing against AI
- **Dynamic Board** - Each player can only have 3 pieces on the board at a time. When placing a 4th piece, the oldest piece automatically disappears
- **Visual Warnings** - Cells that will be removed next are highlighted with a glowing yellow border
- **Win Detection** - Winning combinations are highlighted with a pulsing green animation

### Custom Messages
- Win against AI: "GGWP!"
- Lose against AI: "Amr BAAAL Khelso"
- Two-player win: "[Country] Wins! GGWP!"
- Draw: "It's a Draw!"

## How to Play

1. **Select Game Mode**
   - Choose between playing against AI or with another player

2. **Choose Your Country**
   - Player 1 selects their country
   - In AI mode, select opponent country or use "Random Opponent"
   - In two-player mode, Player 2 also selects their country

3. **Play the Game**
   - Click on any empty cell to place your country's flag
   - Try to get three in a row (horizontally, vertically, or diagonally)
   - Watch for yellow highlighted cells - they'll disappear when the next move is made

4. **Win Conditions**
   - Get three of your country's flags in a row
   - If all 9 cells are filled with no winner, it's a draw

## Technical Details

### Built With
- HTML5
- CSS3 (with custom animations)
- Vanilla JavaScript
- Tailwind CSS (CDN)

### Key Technologies
- CSS Grid for board layout
- CSS Animations for visual effects
- Gradient backgrounds with animated shifting
- Glassmorphism design elements
- Modal popups for game results

### AI Strategy
The AI opponent uses a priority-based decision system:
1. Check for immediate win opportunity
2. Block opponent's winning move
3. Take center position
4. Take available corners
5. Take available side positions

### File Structure
```
tic tac toe/
├── index.html          # Main game file
├── README.md           # This file
└── images/             # Country images directory
    ├── BD.webp
    ├── China.avif
    ├── dick.avif
    ├── india.jpg
    ├── korea.webp
    ├── Russia.webp
    └── USA.jpg
```

## Installation & Usage

1. Clone or download this repository
2. Ensure all country images are in the `images/` folder
3. Open `index.html` in a modern web browser
4. No additional dependencies or installation required

## Browser Compatibility

Works best on modern browsers:
- Chrome/Edge 90+
- Firefox 88+
- Safari 14+
- Opera 76+


