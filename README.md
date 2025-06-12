# Tasks App

A simple and elegant task management application built with Vue 3, TypeScript, and Vite.

## Features

- Create and manage your daily tasks
- Mark tasks as completed
- Filter tasks by status (all, todo, done)
- Visual feedback on task completion progress
- Clean, responsive interface

## Tech Stack

- Vue 3
- TypeScript
- Vite
- CSS transitions

## Getting Started

### Prerequisites

- Node.js (latest LTS version recommended)
- pnpm (package manager)

### Installation

```bash
# Install dependencies
pnpm install
```

### Development

```bash
# Start development server
pnpm run dev
```

### Build for Production

```bash
# Build the application
pnpm run build

# Preview the production build
pnpm run preview
```

## Project Structure

- `src/App.vue` - Main application component
- `src/components/` - Reusable Vue components
  - `TaskForm.vue` - Form for adding new tasks
  - `TaskList.vue` - List of tasks with completion toggle and removal
  - `FilterButton.vue` - Buttons for filtering tasks by status
- `src/types.ts` - TypeScript interfaces and types
