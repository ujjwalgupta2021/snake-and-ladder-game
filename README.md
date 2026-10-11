# Snakes & Ladders

A responsive two-player Snakes and Ladders game built with plain HTML, CSS, and JavaScript. No build tools or dependencies are required.

## Features

- Two-player turn-based gameplay
- Animated dice rolls
- Snakes and ladders with automatic movement
- Exact-roll requirement to reach square 100
- Player position tracking and turn indicators
- Win state and new-game reset button
- Responsive layout for desktop and mobile screens

## Run locally

Open [`index.html`](./index.html) directly in a browser, or serve the project with a local web server:

```bash
python3 -m http.server 4173
```

Then visit [http://localhost:4173](http://localhost:4173).

## How to play

1. Player 1 rolls the dice first.
2. Move the token by the number shown on the dice.
3. Landing on a ladder moves the token up.
4. Landing on a snake moves the token down.
5. The first player to reach square 100 with an exact roll wins.