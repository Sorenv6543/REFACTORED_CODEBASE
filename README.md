# Calendar Booking Application (Refactored)

This is a refactored version of the booking calendar application, focusing on clean architecture, TypeScript, and maintainable code.

## Project Structure##

 Hello this is a test to see if my repos are synced up

```
src/
├── assets/           # Static assets
├── components/       # Reusable UI components
│   ├── auth/         # Authentication components
│   ├── calendar/     # Calendar-specific components
│   ├── ui/           # Base UI components
│   └── layout/       # Layout components
├── composables/      # Reusable logic
├── constants/        # App constants and enums
├── models/           # TypeScript interfaces and types
├── services/         # API and external service integration
├── stores/           # Pinia stores
└── utils/            # Utility functions
```

## Technology Stack

- Vue 3 with Composition API
- TypeScript
- Pinia for state management
- Vue Router
- Vuetify for UI components
- FullCalendar for calendar functionality
- Firebase for backend/authentication

## Development Setup

### Prerequisites
- Node.js (LTS version)
- pnpm

### Installation

```bash
# Install dependencies
pnpm install

# Start development server
pnpm dev

# Build for production
pnpm build

# Preview production build
pnpm preview

# Lint and fix files
pnpm lint

# Format code
pnpm format

# Type check
pnpm typecheck
```

## Using pnpm

This project uses pnpm as the package manager. If you don't have pnpm installed, you can install it globally:

```bash
npm install -g pnpm
```

Or use npx to run it without installing:

```bash
npx pnpm install
```

## Code Conventions

- Use TypeScript for all files
- Follow consistent naming: camelCase for variables/methods, PascalCase for components
- Use Composition API with `<script setup>` syntax
- Document public APIs with JSDoc comments
- Extract reusable logic into composables
- Use interfaces for data models # REFACTORED_CODEBASE
