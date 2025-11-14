# mtg-card-compare

Read a card's oracle text, create a scryfall search string, also show similar cards that cost less money and are less powerful.

## Tech Stack

This is a basic single-page Vue 3 application with:
- **Vue 3** with `<script setup>` composition API
- **TypeScript** for type safety
- **Vite** for fast development and building
- **Tailwind CSS** for styling
- **Material Design color palette** included in Tailwind configuration

## Getting Started

### Install Dependencies
```bash
npm install
```

### Development Server
```bash
npm run dev
```

### Build for Production
```bash
npm run build
```

### Preview Production Build
```bash
npm run preview
```

## Available Material Colors

The project includes a complete Material Design color palette accessible through Tailwind classes:
- `material-red-*`, `material-pink-*`, `material-purple-*`, `material-deep-purple-*`
- `material-indigo-*`, `material-blue-*`, `material-light-blue-*`, `material-cyan-*`
- `material-teal-*`, `material-green-*`, `material-light-green-*`, `material-lime-*`
- `material-yellow-*`, `material-amber-*`, `material-orange-*`, `material-deep-orange-*`
- `material-brown-*`, `material-grey-*`, `material-blue-grey-*`

Each color has shades from 50 to 900 (e.g., `bg-material-blue-500`, `text-material-red-700`).
