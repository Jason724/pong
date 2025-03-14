# Pong Game

A modern, responsive implementation of the classic Pong game with progressive difficulty levels.

## Features

- Responsive design that works on both desktop and mobile devices
- Progressive difficulty - game gets harder as you win
- Supports keyboard controls on desktop
- Touch controls for mobile devices
- Special volume button controls for iOS devices
- Visual enhancements including a center net and score display
- Multiple difficulty levels

## How to Play

### Desktop Controls
- Use the UP and DOWN arrow keys to move your paddle

### Mobile Controls
- On iOS: Use the Volume UP and DOWN buttons (with touch as fallback)
- On other mobile devices: Touch controls

## Game Rules
- First to 5 points wins a round
- Each time you win, the difficulty increases:
  - The ball moves faster
  - Your paddle gets smaller
  - The AI paddle gets slightly larger

## Deployment

This game can be easily deployed on any web hosting service. Since it's a single HTML file with embedded CSS and JavaScript, you just need to upload the `index.html` file.

### GitHub Pages Deployment

1. Fork or clone this repository
2. Enable GitHub Pages in the repository settings
3. Select the main branch as the source
4. Your game will be available at `https://yourusername.github.io/repository-name/`

## Technical Details

The game is built using vanilla JavaScript and HTML5, with no external dependencies. It uses requestAnimationFrame for smooth animations and includes:

- Collision detection
- Physics-based ball movement
- Adaptive AI with randomized behavior
- Responsive design that adjusts to any screen size

## License

This project is open source and available under the MIT License.
