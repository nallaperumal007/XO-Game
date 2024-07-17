
# Tic-Tac-Toe Game

This is a simple implementation of the classic tic-tac-toe game using React and Framer Motion.

## Table of Contents

1. [Demo](#demo)
2. [Features](#features)
3. [Installation](#installation)
4. [Usage](#usage)
5. [Development Flow](#development-flow)
6. [Dependencies](#dependencies)
7. [Contributing](#contributing)
8. [License](#license)

## Demo

https://xo-game-nine-eta.vercel.app/

## Features

- Single-player tic-tac-toe against AI (if applicable).
- Multiplayer mode.
- Animated transitions using Framer Motion.
- Reset game functionality.
- Responsive design.

## Installation

To run this project locally, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/tic-tac-toe-game.git
   cd tic-tac-toe-game
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

## Usage

Once installed, you can start the development server:

```bash
npm run dev
```

This will start the game on `localhost:3000` by default. Open this URL in your browser to play the game.

## Development Flow

### Project Structure

The project is structured as follows:

```
tic-tac-toe-game/
│
├── src/
│   ├── components/
│   │   ├── Button.js
│   │   ├── Square.js
│   ├── App.js
│   ├── index.js
│
├── public/
│   ├── index.html
│
├── package.json
└── README.md
```

- **`src/`**: Contains the main application components and logic.
  - **`components/`**: Contains reusable UI components (`Button.js`, `Square.js`).
  - **`App.js`**: Main application component handling game logic and rendering.
  - **`index.js`**: Entry point for React rendering.

### Tech Stack

- **React**: Frontend library for building user interfaces.
- **Framer Motion**: Used for animations and transitions.
- **Sass**: CSS extension language for styling.

### Development Scripts

- `npm run dev`: Starts the development server using Vite.
- `npm run build`: Builds the production-ready bundle.
- `npm run lint`: Lints the codebase using ESLint.
- `npm run preview`: Previews the production build locally.

## Dependencies

- **framer-motion**: Animation library for React.
- **react**: JavaScript library for building user interfaces.
- **react-dom**: Entry point for DOM-specific methods used in React applications.
- **sass**: CSS extension language.
- **@types/react**: TypeScript type definitions for React.
- **@types/react-dom**: TypeScript type definitions for React DOM.
- **@vitejs/plugin-react**: Vite plugin for React support.
- **eslint**: JavaScript linting utility.
- **eslint-plugin-react**: ESLint plugin for React-specific linting rules.
- **eslint-plugin-react-hooks**: ESLint plugin for React hooks.
- **eslint-plugin-react-refresh**: ESLint plugin for React Refresh support.
- **vite**: Fast, opinionated web dev build tool.

## Contributing

Contributions are welcome! Here's how you can contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/awesome-feature`).
3. Make your changes.
4. Commit your changes (`git commit -am 'Add awesome feature'`).
5. Push to the branch (`git push origin feature/awesome-feature`).
6. Create a new Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---
