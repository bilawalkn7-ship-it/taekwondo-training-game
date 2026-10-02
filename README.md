# Taekwondo Training Game Design

## Project Goal
This project is a browser-based martial arts learning simulator. It teaches Taekwondo fundamentals using a data-driven approach that emphasizes safe technique, disciplined movement, and skill progression.

## Recommended Engine
Phaser 4 is the recommended framework for the MVP because it balances ease of use, browser support, and community tooling. It is ideal for 2D fighting drills, practice flows, and a simple AI opponent.

## Architecture
- `src/data` stores technique definitions and challenges
- `src/game` contains logic for progress, combat, training, and AI
- `src/ui` handles menus, lesson panels, and training surfaces
- `src/main.js` boots the application and manages mode changes

## Folder Structure
- `index.html`
- `styles.css`
- `src/data/techniques.js`
- `src/data/lessons.js`
- `src/data/challenges.js`
- `src/data/progression.js`
- `src/game/logic/gameState.js`
- `src/game/player/playerController.js`
- `src/game/ai/aiController.js`
- `src/game/combat/combatSystem.js`
- `src/game/training/trainingSystem.js`
- `src/game/progress/progressSystem.js`
- `src/ui/uiManager.js`
- `src/main.js`
- `docs/design.md`

## Safety & Education Principles
- Show correct body position and distances
- Emphasize controlled movement over brutality
- Avoid dangerous or unrealistic fighting patterns
- Explicitly state that the game is educational and not a replacement for instruction from a qualified coach

## MVP Scope
- Main menu
- Technique lessons
- Front kick practice drill
- Basic AI sparring
- Progress tracking
- Safety and educational guidance

## Planned Expansion
- More techniques and lessons
- More advanced AI behavior and counters
- Audio cues and animation polish
- Personalized challenge system
- Responsive design and accessibility polish
- Localization and more training programs
