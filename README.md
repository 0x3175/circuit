# circuit

An interval timer app for circuit training exercises.

![circuit-screenshot](./screenshot.png)

## Tech Stack

- **Framework**: [React 19](https://react.dev/)
- **Build Tool**: [Vite 7](https://vitejs.dev/)
- **Styling**: [Sass](https://sass-lang.com/)
- **PWA**: [vite-plugin-pwa](https://vite-pwa-org.netlify.app/)
- **Utilities**: [NoSleep.js](https://github.com/richtr/NoSleep.js)
- **Deployment**: [Surge](https://surge.sh/)

## Getting Started

### Installation

The project uses `npm install --legacy-peer-deps` to handle dependency resolution in the latest Vite environment. A custom install script is provided:

```bash
npm run install
```

### Available Scripts

- `npm run dev`: Start the development server.
- `npm run build`: Build the app for production (output to `/dist`).
- `npm run preview`: Preview the production build locally.
- `npm run pub`: Deploy the production build to surge.sh.

## PWA Features

This app is a fully functional Progressive Web App (PWA) with:
- Offline support via service workers.
- Add to Home Screen (A2HS) capabilities.
- Modernized PWA management using `vite-plugin-pwa`.
