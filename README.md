# Welcome to my Portfolio Project project

A modern, responsive portfolio website built with **React**, **TypeScript**, **Tailwind CSS**, and **Framer Motion**. Features a dynamic theme toggle (light/dark) using React Context API, smooth animations, and a clean component-based architecture.
---

## Tech Stack

- **React** (with TypeScript) – UI library
- **Vite** – Build tool
- **Tailwind CSS** – Utility-first styling
- **Framer Motion** – Animations
- **Lucide React** – Icons
- **React Context API** – Theme state management
- **ESLint / Prettier** – Code quality (optional)

---

## Project Structure
portfolio/
├── public/ # Static assets
├── src/
│ ├── assets/ # Images, fonts, etc.
│ ├── components/ # Reusable React components
│ │ ├── Navbar.tsx
│ │ ├── Hero.tsx
│ │ ├── About.tsx
│ │ ├── Skills.tsx
│ │ ├── Projects.tsx
│ │ ├── Certifications.tsx
│ │ ├── Achievements.tsx
│ │ ├── Contact.tsx
│ │ ├── Footer.tsx
│ │ ├── ScrollProgress.tsx
│ │ └── InteractiveBackground.tsx
│ ├── context/ # Context providers
│ │ └── ThemeContext.tsx
│ ├── App.tsx # Root component with ThemeProvider
│ ├── main.tsx # Entry point
│ ├── index.css # Global styles & Tailwind imports
│ └── vite-env.d.ts # Vite type definitions
├── tailwind.config.ts # Tailwind configuration
├── tsconfig.json # TypeScript configuration
├── vite.config.ts # Vite configuration
├── package.json # Dependencies & scripts
├── .gitignore # Ignored files (includes .env)
└── README.md # This file

---

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
