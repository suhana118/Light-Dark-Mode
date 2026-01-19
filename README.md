Navbar in React JS | Light & Dark Mode Navigation Bar

A responsive navigation bar built with React JS featuring light and dark mode switching, with theme preference persisted using localStorage. This project demonstrates clean component structure, modern UI styling, and practical state management in a React + Vite setup.

Features

 * Responsive Navigation BarA modern navbar layout including a logo, navigation menu links, a search box, and a theme toggle button.

 * Light and Dark ModeAllows users to switch between light and dark themes with a single click.

 * Theme PersistenceThe selected theme is stored in the browser’s local storage and remains active even after page reloads or browser restarts.

 * Dynamic Theme IndicatorThe toggle indicator updates automatically based on the currently active theme.


Technologies Used

* React JS – User interface development

* Vite – Fast development and build tool

* CSS – Styling and layout


Project Structure

src/
│── App.jsx                     # Main application component
│── main.jsx                    # Application entry point
│── index.css                   # Global styles
│
├── components/
│   └── Navbar/
│       ├── Navbar.jsx          # Navbar component and theme logic
│       └── Navbar.css          # Navbar-specific styles
│
└── assets/                      # Images and icons


Implementation Overview

1. Project initialization using Vite and React

2. Removal of default boilerplate files

3. Creation of a reusable Navbar component

4. Navbar layout with logo, navigation links, search input, and theme toggle

5. Asset integration for logos and icons

6. Styling using CSS

7. Light and dark mode implementation using useState

8. Theme state management in App.jsx and prop passing to Navbar.jsx

9. Theme persistence using localStorage with useEffect


SCREENSHORTS

1. Light Mode Navbar


<img width="1915" height="904" alt="Screenshot 2026-01-19 132725" src="https://github.com/user-attachments/assets/edfaa48e-08ea-49f1-8590-09e2ae0775d8" />


2. Dark Mode Navbar


<img width="1908" height="908" alt="Screenshot 2026-01-19 132614" src="https://github.com/user-attachments/assets/16d96eb3-9f06-4f8e-808f-43f63d533c34" />












# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Babel](https://babeljs.io/) (or [oxc](https://oxc.rs) when used in [rolldown-vite](https://vite.dev/guide/rolldown)) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## React Compiler

The React Compiler is currently not compatible with SWC. See [this issue](https://github.com/vitejs/vite-plugin-react/issues/428) for tracking the progress.

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript with type-aware lint rules enabled. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) for information on how to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.
