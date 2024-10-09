# Moving Ball

This project is a simple web animation that moves a ball diagonally across the screen. It uses basic HTML, CSS, and JavaScript to animate the ball's movement and handle the bouncing effect when it hits the edges of the screen.

## Features

- Ball moves in a diagonal direction across the screen.
- The ball changes direction when it hits any of the screen's boundaries.
- Uses simple and efficient JavaScript logic to control the animation.

## How It Works

1. A `div` element styled as a circle represents the ball.
2. JavaScript controls the ball's movement by continuously updating its `left` and `top` positions.
3. The ball reverses its direction when it reaches the edge of the screen (top, bottom, left, or right).

## Code Breakdown

### HTML

The HTML structure is simple, containing a single `div` element with the `id="ball"`, which is animated.

```html
<div id="ball"></div>
