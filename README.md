# Flappy Bird Game (Phaser 3)

A simple Flappy Bird style browser game built with Phaser 3 and JavaScript.

The player controls a bird, avoids obstacles, and tries to reach the finish area without crashing.

## Features

- Phaser 3 arcade physics
- Gravity and jump controls
- Ground and obstacle collision detection
- Start instruction prompt
- Lose condition when hitting ground or columns
- Win condition when the bird reaches the far right side

## Tech Stack

- JavaScript
- Phaser 3 (CDN)
- HTML

## Project Structure

```
flappy_bird/
	index.html
	app.js
	README.md
	assets/
```

## How To Run

You can run this game with any static file server.

### Option 1: Python HTTP server

```bash
cd flappy_bird
python3 -m http.server 5500
```

Open:

http://localhost:5500

### Option 2: Open directly

Open `index.html` in a browser.

## Controls

- Space: start the game
- Up arrow: make the bird fly upward

## Gameplay Rules

- The bird stays still until the game starts.
- After starting, the bird moves forward automatically.
- If the bird hits the ground or columns, the game is over.
- If the bird reaches the right side of the map, you win.

## Notes

- Phaser is loaded from CDN in `index.html`.
- Main game logic is in `app.js`.

## Future Improvements

- Add score system
- Add restart button
- Randomize obstacle positions
- Add sound effects and animations
- Improve UI and game over screen
