# HP_ScoreWise

[![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)](https://reactjs.org/)
[![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)](https://vitejs.dev/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)
[![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)

**HP_ScoreWise** is a modern, minimalist assessment platform designed for educational institutions. It streamlines the evaluation process by providing intuitive tools for teachers to create assessments and for students to submit and review their performance.

---

## Features

### For Teachers
- **Easy Assessment Creation**: Build comprehensive assessments with various question types.
- **Marking Schemes**: Define clear evaluation criteria and correct answers.
- **Automated Feedback**: Reduce manual grading time with system-assisted evaluation.
- **Student Management**: Monitor submissions and results in a centralized dashboard.

### For Students
- **Intuitive Interface**: Access and take assessments through a clean, distraction-free environment.
- **Instant Submissions**: Securely upload and submit answers.
- **Detailed Analytics**: View scores, correct answers, and personalized performance feedback.
- **Dashboard Overview**: Keep track of pending and completed assessments.

---

## UI & Design

Inspired by the clean, high-contrast aesthetic of **ChatGPT**, the UI features:
- **Monochrome Palette**: A professional black-and-white theme for maximum focus.
- **Minimalist Components**: Sleek, flat design elements using custom Tailwind utilities.
- **Responsive Layout**: Seamless experience across mobile, tablet, and desktop devices.

---

## Tech Stack

- **Frontend**: React 18 with TypeScript
- **Build Tool**: Vite
- **Styling**: Tailwind CSS (Monochrome Design System)
- **Icons**: Lucide React
- **State Management**: Zustand
- **Routing**: React Router DOM

---

## Getting Started

### Prerequisites
- [Node.js](https://nodejs.org/) (v18 or higher recommended)
- [npm](https://www.npmjs.com/)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Harsh-PAHADIA/HP_ScoreWise.git
   cd HP_ScoreWise
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the development server:
   ```bash
   npm run dev
   ```

4. Build for production:
   ```bash
   npm run build
   ```

---

## Project Structure

```text
src/
├── components/     # Reusable UI elements (Button, Card, etc.)
│   ├── auth/       # Login and Registration forms
│   ├── Layout/     # Header, Footer, and Main Layout
│   ├── student/    # Student-specific components
│   └── teacher/    # Teacher-specific components
├── pages/          # Main application views
├── store/          # Zustand state management
├── types/          # TypeScript definitions
├── lib/            # Utility functions
└── index.css       # Global styles & Tailwind directives
```

---

## License

Distributed under the MIT License. See `LICENSE` for more information.

---

Built with focus by [Harsh Pahadia](https://github.com/Harsh-PAHADIA)
