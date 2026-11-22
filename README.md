# Animator

A browser-based drawing animator built with Gleam and Lustre for UC Berkeley CS 61A.

[Open the app](https://esonhjz.github.io/animator/)

## Features

- Edit Gleam drawing code and see the animation update.
- Adjust the shape and animation speed with sliders.
- Play animations backward with a negative speed, or pause at zero.
- Create and switch between named drawings.
- Automatically save drawings in your browser across page reloads.
- Repeat drawings around the center with Ripple Kaleidoscope and optional alternating reflection.
- Click the canvas to create overlapping ripples with adjustable distortion strength.
- Independently control automatic rotation and path playback.

## Usage

Choose a drawing from the menu or select **New drawing…** to create one. Edit the code and use the sliders to explore the result. Code errors appear beside the editor.

Click **Load flower demo** to open the custom petal drawing. Adjust **Copies** and **Alternate mirror** to explore its symmetry, then click the canvas to create water-like ripples. **Ripple** controls distortion strength. **Pause rotation** and **Rotation** control the pattern's rotation independently of the bottom path-playback **Speed** slider. Enable **Kaleidoscope** on any drawing to use the extension with your own code.

Drawings are stored locally in your browser. They are specific to the browser and site address and do not sync between devices.

## Repository

This repository contains the published web files and is hosted on GitHub Pages.
