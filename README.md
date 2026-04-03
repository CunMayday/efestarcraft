# StarCraft x Pokémon Prototype

This project is a web-based game prototype that combines elements from StarCraft and Pokémon into a single interactive experience. It features a sci-fi inspired user interface, interactive map, and detailed unit stats and combat options.

## Features

- **Sci-Fi User Interface**: A customized UI using Tailwind CSS with unique fonts (`Orbitron`, `Rajdhani`), neon colors, scanlines, and animated components to give a futuristic feel.
- **Interactive Map**: A top-down tactical view where units are rendered as animated SVG sprites with health bars.
- **Unit Selection & Details**: Clicking on a unit reveals its details in the bottom console (similar to StarCraft 2). This includes:
  - Unit Name, Level, Type (e.g., Psychic/Steel), and Description.
  - Health (HP) and Energy bars.
  - A dynamic video portrait of the selected unit.
- **Combat Commands**: A moveset panel inspired by Pokémon, displaying 4 distinct abilities for each unit along with their Power Points (PP).
- **Video Portraits**: The prototype uses local `.mp4` video files (e.g., `chaosmarineportrait.mp4`) as animated portraits for units, bringing them to life in the communications console.

## Technologies Used

- HTML5
- CSS3 (with Tailwind CSS via CDN)
- Vanilla JavaScript

## How to Run

1. Ensure you have the project files downloaded, specifically `index.html` and the required video asset `chaosmarineportrait.mp4` in the same directory.
2. Open `index.html` in any modern web browser.
3. Click on the animated unit tokens on the grid map to select them and view their detailed stats and video portraits.

## Project Structure

- `index.html`: Contains all the markup, styling, and JavaScript logic for the game prototype.
- `chaosmarineportrait.mp4`: A local video file used as the animated portrait when units are selected.
