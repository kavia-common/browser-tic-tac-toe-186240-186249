# Tic Tac Toe – React Frontend

## Overview
A simple browser-based Tic Tac Toe with a 3×3 grid for two players. Players take turns placing X and O, with automatic win/draw detection and a quick way to reset. The UI follows a clean, modern light theme.

## Features
- Playable 3×3 grid with two-player turns
- Current player indicator
- Win and draw detection
- Reset game button

## Tech Stack
- React (web)
- Single frontend container
- Preview on port 3000

## Getting Started
Previews are started by the user. To run locally:
1. Install dependencies: npm install
2. Start preview: npm start
3. Open http://localhost:3000

## Usage
- Click a square to place X or O.
- Turns alternate automatically.
- Use “Reset” to start a new game.

## Project Structure
- src/
  - components/ – UI pieces (board, square, status)
  - hooks/ – game state and helpers
  - utils/ – winner/draw logic and helpers

## Environment Variables (optional)
The app runs fine without any variables. If needed, you can set:
- REACT_APP_API_BASE
- REACT_APP_BACKEND_URL
- REACT_APP_FRONTEND_URL
- REACT_APP_WS_URL
- REACT_APP_NODE_ENV
- REACT_APP_NEXT_TELEMETRY_DISABLED
- REACT_APP_ENABLE_SOURCE_MAPS
- REACT_APP_PORT
- REACT_APP_TRUST_PROXY
- REACT_APP_LOG_LEVEL
- REACT_APP_HEALTHCHECK_PATH
- REACT_APP_FEATURE_FLAGS
- REACT_APP_EXPERIMENTS_ENABLED

## Contributing
PRs welcome! Future ideas: AI opponent, score tracking, animations.
