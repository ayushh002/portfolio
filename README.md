# Welcome to my Portfolio Project project

This portfolio website is a modern, responsive single‑page application built with React, TypeScript, Vite, Tailwind CSS, and Framer Motion. It showcases my skills, projects, certifications, and achievements in a clean, interactive layout. The design features a light/dark theme toggle that persists using localStorage, smooth animations, an interactive background with animated blobs, and a scroll progress indicator. All components are reusable, typed with TypeScript, and follow a component‑based architecture.

The theme system is implemented with React’s Context API and CSS custom properties. The ThemeProvider manages the theme state and applies a dark class to the <html> element when dark mode is active. Tailwind CSS is configured with darkMode: "class", so all utility classes automatically respond to the theme change. The color scheme is defined using HSL variables in the global CSS, making it easy to customize. The user’s preference is saved in localStorage, so the chosen theme persists across page reloads.

---

## Tech Stack

- **React** (with TypeScript) – UI library
- **Vite** – Build tool
- **Tailwind CSS** – Utility-first styling
- **Framer Motion** – Animations
- **Lucide React** – Icons
- **React Context API** – Theme state management
- **ESLint / Prettier** – Code quality (optional)


## Getting Started

### Prerequisites

- **Node.js** (v16 or later)
- **npm** or **yarn** or **pnpm**

### Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/portfolio.git
cd portfolio

# Install dependencies
npm install

# Running the Development Server
npm run dev
