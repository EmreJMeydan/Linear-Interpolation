# Linear Interpolation (Lerp)

A JavaScript project demonstrating linear interpolation (lerp) through animated movement, colour transitions, sound frequency changes, and text animations.

## Overview

This project uses HTML Canvas and JavaScript to demonstrate how linear interpolation can smoothly transition between two values over time.

A point moves back and forth between two positions while the background colour changes between orange and blue. The project also includes an interactive sound feature that changes frequency and a text animation that uses lerp to adjust its dash pattern.

## The Mathematics

Linear interpolation calculates a value between a starting value and an ending value using a parameter `t`.

The formula is:

$$
\operatorname{lerp}(a,b,t)=a+(b-a)t
$$

Where:

- `a` — The starting value.
- `b` — The ending value.
- `t` — The interpolation parameter, typically between `0` and `1`.

For example:

- When `t = 0`, the result is `a`.
- When `t = 0.5`, the result is halfway between `a` and `b`.
- When `t = 1`, the result is `b`.

## Features

- Animates a point between two positions using linear interpolation.
- Smoothly transitions the background colour between two colours.
- Changes sound frequency using interpolated values.
- Animates text using a changing line dash pattern.
- Uses a shared `lerp()` function for different types of values.
- Uses `requestAnimationFrame()` to update the animation continuously.
- Enables sound when the canvas is clicked.

## Technologies Used

- HTML
- CSS
- JavaScript
- HTML Canvas API
- Web Audio API

## How to Run

1. Clone or download this repository.
2. Open the `index.html` file in a web browser.
3. Watch the point, background colour, and text animate.
4. Click the canvas to enable the sound feature.

## How It Works

The `lerp()` function calculates a value between two numbers. The `vLerp()` function applies linear interpolation to objects containing multiple values, such as coordinates and RGB colour components.

A sine function generates a value that smoothly moves between `0` and `1`, allowing the animations to repeat continuously in both directions.
