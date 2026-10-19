# Chatbot Project

A simple rule-based chatbot built with React and Vite. It is not powered by an LLM. I built it to practice React fundamentals: components, state, hooks, effects and custom hooks.

**Live demo:** https://chatbot-project-dusky.vercel.app/

## Features

- Greetings
- Dice throw
- Coin toss
- Current date
- Chat view that auto-scrolls to the latest message using a custom hook (`useAutoScroll`)

## What I practiced

- Setting up a React project with Vite
- Splitting the UI into reusable components
- Managing the message list with `useState`
- Running side effects with `useEffect`
- Writing a custom hook, `useAutoScroll`, to keep the newest message in view
- Deploying a Vite build to Vercel

## Tech stack

- React
- Vite
- JavaScript
- ESLint
- Vercel (hosting)

## Run locally

```bash
git clone https://github.com/jerishimmanuel/chatbot-project.git
cd chatbot-project
npm install
npm run dev
```

Then open the local URL that Vite prints in the terminal (usually http://localhost:5173).

## Build for production

```bash
npm run build
```

## Project structure

```
chatbot-project/
├── public/        # static assets
├── src/           # components, hooks and app code
├── index.html
├── vite.config.js
└── package.json
```

## Author

Jerish Immanuel
GitHub: https://github.com/jerishimmanuel
