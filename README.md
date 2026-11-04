# Weather App

A weather application built with Vite + React + TypeScript.

## Tech Stack

- Vite + React + TypeScript
- shadcn/ui
- Tailwind CSS
- TanStack Query
- React Hook Form
- Zustand
- ESLint

## Installation

```bash
npm install
```

## Development

```bash
npm run dev
```

## Build

```bash
npm run build
```

## Preview

```bash
npm run preview
```

## Lint

```bash
npm run lint
```

## Project Structure

```
src/
├── assets/          # Static assets
├── components/
│   ├── ui/          # shadcn/ui components
│   ├── layout/      # Layout components
│   └── feature/     # Feature components
├── hooks/           # Custom hooks
├── lib/             # Utilities (cn, etc.)
├── stores/          # Zustand stores
├── types/           # TypeScript types
├── services/        # API calls
├── App.tsx
└── main.tsx
public/
├── assets/          # Static assets (images, fonts, icons)
└── favicon.svg
```

## Assets & Design

- `assets/` - Original assets (images, fonts)
- `design/` - Design mockups/screenshots
- `style-guide.md` - Style guide (colors, typography, layout)
- Assets are also available in `public/assets/` for static serving
