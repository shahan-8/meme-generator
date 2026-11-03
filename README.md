# Meme Generator

A simple meme generator built with React and Vite. The app is organized into reusable interface components, including a header and the main meme creation area.

## Features

- React component-based interface
- Separate header and main content components
- Fast local development with Vite
- Modern React 19 setup

> The README documents the current project structure. Add screenshots and a detailed feature list as the app evolves.

## Tech Stack

- React 19
- JavaScript (JSX)
- Vite
- Oxlint

## Getting Started

### Prerequisites

- Node.js (LTS recommended)
- npm

### Installation

```bash
git clone https://github.com/shahan-8/meme-generator.git
cd meme-generator
npm install
npm run dev
```

Open the local URL printed by Vite.

## Production Build

```bash
npm run build
npm run preview
```

## Available Scripts

| Command | Description |
| --- | --- |
| `npm run dev` | Start the development server |
| `npm run build` | Build the app for production |
| `npm run lint` | Run Oxlint |
| `npm run preview` | Preview the production build |

## Project Structure

```text
meme-generator/
├── src/
│   ├── components/   # Reusable interface components
│   ├── App.jsx       # Main application composition
│   └── main.jsx      # React entry point
├── public/
├── index.html
└── package.json
```

## Author

Built by [Shahan](https://github.com/shahan-8).