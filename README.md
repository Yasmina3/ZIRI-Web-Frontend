# ZIRI — Web Application

A modern web frontend built with React and Vite, featuring a component-based architecture, responsive styling, interactive UI elements, and integration with the Base44 platform.

## Overview

ZIRI is a web application developed using a modern JavaScript frontend stack.

The project uses React for building reusable user interface components and Vite for fast development and optimized production builds.

Its frontend architecture incorporates a collection of UI libraries, form-management tools, animations, and data-visualization components to support the development of an interactive web experience.

## Technology Stack

| Technology | Purpose |
|---|---|
| JavaScript | Main programming language |
| React 18 | UI development |
| Vite 6 | Development server and build tooling |
| Tailwind CSS 3 | Utility-first styling |
| Radix UI | Accessible UI primitives |
| Framer Motion | UI animations |
| React Router | Client-side routing |
| React Hook Form | Form management |
| Zod | Data validation |
| Recharts | Data visualization |
| Lucide React | Icons |
| Base44 SDK | Platform and backend integration |

## Project Structure

```text
ZIRI-Web-Frontend/
│
├── src/                  # Application source code
│
├── public/               # Static assets (if present)
│
├── index.html            # HTML entry point
│
├── package.json          # Dependencies and scripts
├── vite.config.js        # Vite configuration
├── tailwind.config.js    # Tailwind configuration
├── postcss.config.js     # PostCSS configuration
├── eslint.config.js      # Code quality configuration
│
└── README.md
```

## Getting Started

### Prerequisites

- Node.js
- npm

### Installation

Clone the repository:

```bash
git clone https://github.com/Yasmina3/ZIRI-Frontend.git
```

Navigate to the project directory:

```bash
cd ZIRI-Frontend
```

Install dependencies:

```bash
npm install
```

### Run Development Server

```bash
npm run dev
```

Vite will start the local development server and provide a URL in the terminal.

### Build for Production

```bash
npm run build
```

### Preview Production Build

```bash
npm run preview
```

### Code Quality

Run ESLint:

```bash
npm run lint
```

## Architecture

The application follows a React-based frontend architecture, using reusable components and dedicated libraries for:

- User interface development.
- Styling and responsive layouts.
- Client-side navigation.
- Form handling and validation.
- Animations and interactive elements.
- Data visualization.
- Integration with Base44 services.

## Development

The project uses Vite to provide a fast development environment and an optimized production build.

Dependencies and development scripts are managed through `package.json`.

## License

No license has currently been specified for this repository.
