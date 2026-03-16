# nota 📝

A clean, minimal note-taking app built with React + Vite.

## Features

- ✍️ Create, edit, and delete notes
- 🔍 Real-time search across titles, content, and tags
- 🏷️ Tag system — add tags with Enter, remove with backspace or click
- 💾 Auto-save with localStorage persistence (notes survive page refresh)
- 📊 Live word & character count
- ⚡ Fast and lightweight — no external state libraries

## Tech Stack

- **React 18** — UI components
- **Vite 5** — build tool & dev server
- **CSS Modules** — scoped component styles
- **uuid** — unique note IDs
- **localStorage** — client-side persistence

## Getting Started

```bash
# Install dependencies
npm install

# Start dev server
npm run dev

# Build for production
npm run build

# Preview production build
npm run preview
```

## Project Structure

```
nota/
├── public/
│   └── favicon.svg
├── src/
│   ├── components/
│   │   ├── Sidebar.jsx       # Note list + search
│   │   ├── Sidebar.module.css
│   │   ├── Editor.jsx        # Note editor with tags
│   │   ├── Editor.module.css
│   │   ├── EmptyState.jsx    # Shown when no note selected
│   │   └── EmptyState.module.css
│   ├── App.jsx               # Root component, state management
│   ├── App.module.css
│   ├── index.css             # Global styles & CSS variables
│   └── main.jsx              # Entry point
├── index.html
├── vite.config.js
├── package.json
└── .gitignore
```

## License

MIT
