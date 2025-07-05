<<<<<<< HEAD
# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript with type-aware lint rules enabled. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) for information on how to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.
=======
# React Project Structure

This is a modern React project powered by Vite and integrated with several essential libraries and tools to support scalable frontend development.

## 🔧 Tech Stack

- **React 19**
- **Vite** – Fast dev/build tool
- **Tailwind CSS** – Utility-first CSS framework
- **ShadCN UI** – Component library based on Radix UI
- **TanStack React Query** – Powerful async state management
- **React Router v7** – Client-side routing
- **AOS** – Animate on scroll library
- **Lucide Icons** – Icon library
- **React Hot Toast** – Toast notifications
- **ESLint** – Linting for clean code

---

## 📁 Project Structure
.
├── public/ # Static assets
├── src/
│ ├── assets/ # Images, fonts, etc.
│ ├── components/ # Reusable components
│ ├── layout/ # Layout components (headers, sidebars)
│ ├── lib/ # Utility functions, API clients
│ ├── pages/ # Route-level pages
│ ├── routes/ # App routes config
│ ├── shared/ # Shared UI like buttons, inputs
│ ├── App.css # Global styles
│ ├── index.css # Tailwind base + custom styles
│ ├── main.jsx # App entry point
├── components.json # ShadCN configuration
├── vite.config.js # Vite configuration
├── eslint.config.js # Linting rules
├── jsconfig.json # Path aliases and IntelliSense support
├── index.html # Main HTML entry
└── package.json # Dependencies and scripts


---

##  Getting Started

### 1. Install Dependencies

```bash
npm install



### 2. Run Dev Server

```bash
npm run dev



### 3. Build for Production

```bash
npm run build

---

### 4.Preview Production Build

```bash
npm run preview

