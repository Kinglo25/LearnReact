# LearnReact — React.dev Tic-Tac-Toe

This repo contains the **Tic-Tac-Toe** game built by following the official React.dev tutorial.

- Tutorial: https://react.dev/learn/tutorial-tic-tac-toe

## Prerequisites

- Node.js + npm installed

## Getting started

Install dependencies:

```bash
npm install
```

Start the dev server:

```bash
npm start
```

Then open the URL shown in the terminal (usually http://localhost:3000).

## Available scripts

- `npm start` — run the app in development mode
- `npm test` — run tests in watch mode
- `npm run build` — create a production build in `build/`

## Project notes

- Main app code: `src/App.js`
- This project uses `react-scripts` (Create React App tooling).

## What this project practices

- Components and props
- State with `useState`
- Handling events (e.g. `onClick`)
- Rendering lists with `key`
- Immutability patterns (copying arrays before updating)
- Lifting state up (game state owned by the parent component)