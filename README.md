# Advice Generator React

A React rebuild of my original Advice Generator App, created as a hands-on practice project to learn modern React application structure and best practices.

This project focuses on:
- clean folder structure
- component-based architecture
- reusable UI patterns
- custom hooks
- API integration
- scalable React project organization

The goal is not just to recreate the UI, but to rebuild the app in a more maintainable and production-friendly way using React.


## Folder Structure

src/
├─ app/
│  ├─ App.jsx
│  ├─ main.jsx
│  └─ styles/
│     └─ globals.css
├─ assets/
│  └─ images/
├─ features/
│  └─ advice/
│     ├─ components/
│     │  └─ AdviceCard.jsx
│     ├─ hooks/
│     │  └─ useAdvice.js
│     ├─ services/
│     │  └─ adviceApi.js
│     ├─ styles/
│     │  └─ AdviceCard.module.css
│     └─ index.js
└─ shared/
   └─ utils/

### Structure Philosophy

This project follows a lightweight feature-based structure:

- `app/` → application entry, root app setup, and global styles
- `assets/` → images, icons, and static resources
- `features/advice/` → all logic related to the advice generator feature
- `components/` → UI parts for the feature
- `hooks/` → custom React hooks for state and behavior
- `services/` → API calls and external data handling
- `styles/` → feature-scoped styling
- `shared/` → reusable helpers and utilities for future scaling