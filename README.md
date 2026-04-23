# 🤖 Learn AI — Master Artificial Intelligence

A modern, interactive web application for learning Artificial Intelligence concepts, built with React, TypeScript, Vite, and Tailwind CSS.

---

## 🚀 Tech Stack

| Technology | Version | Purpose |
|---|---|---|
| React | 18.2.0 | UI framework |
| TypeScript | 4.9.5 | Type safety |
| Vite | 4.5.0 | Build tool & dev server |
| Tailwind CSS | 3.3.0 | Utility-first styling |
| React Router DOM | ^6.21.0 | Client-side routing |
| Framer Motion | ^12.38.0 | Animations |
| Recharts | ^2.10.0 | Data visualization |
| Lucide React | ^1.8.0 | Icon library |
| React YouTube | ^10.1.0 | YouTube video embeds |
| clsx + tailwind-merge | latest | Conditional class utilities |

---

## 📁 Project Structure

```
learn-ai/
├── index.html              # App entry point
├── package.json            # Dependencies & scripts
├── vite.config.ts          # Vite + path alias config
├── tailwind.config.js      # Tailwind configuration (dark mode enabled)
├── postcss.config.js       # PostCSS configuration
├── tsconfig.json           # TypeScript configuration
└── src/                    # Application source code
    └── main.tsx            # React app bootstrap
```

---

## ⚙️ Getting Started

### Prerequisites

- **Node.js** v16 or higher
- **npm** v7 or higher

### Installation

```bash
# 1. Clone the repository
git clone <your-repo-url>
cd learn-ai

# 2. Install dependencies
npm install

# 3. Start the development server
npm run dev
```

The app will be available at **(http://127.0.0.1:5175/)**

---

## 📜 Available Scripts

| Command | Description |
|---|---|
| `npm run dev` | Start local development server with HMR |
| `npm run build` | Build optimized production bundle |
| `npm run preview` | Preview the production build locally |

---

## 🛣️ Path Aliases

The project uses the `@/` alias mapped to the `src/` directory for clean imports:

```ts
// Instead of:
import Component from '../../components/Component'

// Use:
import Component from '@/components/Component'
```

---

## 🌙 Dark Mode

Dark mode is supported via Tailwind's `class` strategy. Toggle the `dark` class on the root `<html>` element to switch themes.

---

## 🏗️ Building for Production

```bash
npm run build
```

Output will be generated in the `dist/` folder, ready to deploy to any static hosting provider (Vercel, Netlify, GitHub Pages, etc.).
