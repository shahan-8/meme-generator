# Meme Generator

A simple meme generator built with React and Vite. Create memes by adding custom top and bottom text to meme images.

## Preview

### Example 1

![Meme Generator preview - One does not simply walk into Mordor](screenshots/meme-generator-1.jpg)

### Example 2

![Meme Generator preview - custom meme text](screenshots/meme-generator-2.jpg)

## Features

- React component-based interface
- Add custom top and bottom text to meme images
- Generate a new meme image
- Separate header and main content components
- Fast local development with Vite

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
├── screenshots/
│   ├── meme-generator-1.jpg
│   └── meme-generator-2.jpg
├── src/
│   ├── components/
│   ├── App.jsx
│   └── main.jsx
├── public/
├── index.html
└── package.json
```

## Author

Built by [Shahan](https://github.com/shahan-8).