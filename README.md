# Vite + React + SWC

This is a Vite React project using the **Rust-based SWC compiler** for blazing fast builds and hot module replacement (HMR).

## Features

- ⚡️ **Vite** - Lightning fast build tool
- ⚛️ **React 18** - Latest React version
- 🦀 **SWC** - Super fast Rust-based compiler
- 🔥 **Hot Module Replacement** - Instant updates during development
- 📦 **Optimized Build** - Production-ready builds

## Getting Started

### Prerequisites

- Node.js 16+ installed
- npm or yarn package manager

### Installation

```bash
# Install dependencies
npm install

# Start development server
npm run dev

# Build for production
npm run build

# Preview production build
npm run preview
```

## Why SWC?

SWC (Speedy Web Compiler) is a Rust-based compiler that is **20x faster than Babel**. It provides:

- Faster compilation times
- Better development experience
- Lower memory usage
- Full TypeScript and JSX support

## Project Structure

```
.
├── src/
│   ├── App.jsx          # Main App component
│   ├── App.css          # App styles
│   ├── main.jsx         # Application entry point
│   └── index.css        # Global styles
├── index.html           # HTML template
├── package.json         # Dependencies and scripts
└── vite.config.js       # Vite configuration with SWC
```

## Available Scripts

- `npm run dev` - Start development server at http://localhost:5173
- `npm run build` - Build for production
- `npm run preview` - Preview production build locally
- `npm run lint` - Run ESLint

## Learn More

- [Vite Documentation](https://vitejs.dev/)
- [React Documentation](https://react.dev/)
- [SWC Documentation](https://swc.rs/)

## License

MIT
