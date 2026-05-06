# NavHero

A modern navbar and hero component project built with React, TypeScript, Tailwind CSS, and Vite.

## Prerequisites

- Node.js (v16 or higher)
- npm or yarn

## Installation

1. Install dependencies:
```bash
npm install
```

## Running the Project

### Development
Start the development server:
```bash
npm run dev
```

This will start the Vite development server, typically at `http://localhost:5173`

### Build
Build for production:
```bash
npm run build
```

### Preview
Preview production build locally:
```bash
npm run preview
```

### Linting
Run ESLint to check code quality:
```bash
npm run lint
```

## Project Structure

```
NavHero/
├── src/
│   ├── components/
│   │   ├── Hero.tsx
│   │   └── Navbar.tsx
│   ├── store/
│   │   ├── authStore.ts
│   │   └── menuStore.ts
│   ├── App.tsx
│   ├── main.tsx
│   └── index.css
├── index.html
├── package.json
├── tsconfig.json
├── vite.config.ts
└── eslint.config.js
```

## Technologies Used

- **React 19.2.5** - UI library
- **TypeScript 6.0.2** - Type safety
- **Tailwind CSS 4.2.4** - Styling
- **Vite 8.0.10** - Build tool
- **Zustand 5.0.13** - State management
- **ESLint** - Code linting

## Features

- Modern hero section component
- Responsive navbar component
- State management with Zustand
- Tailwind CSS for styling
- TypeScript for type safety
- Vite for fast development and builds

## License

MIT
