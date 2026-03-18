# Construction Closing Docs Web Application

A simple Angular application featuring a "Coming Soon" landing page for Construction Closing Docs.

## Prerequisites

- Node.js (v18 or higher)
- npm (v9 or higher)

## Installation

1. Install dependencies:
```bash
npm install
```

## Development

Run the development server:
```bash
npm start
```

The application will be available at `http://localhost:4200/`

## Build

Build the application for production:
```bash
npm run build
```

The build artifacts will be stored in the `dist/` directory.

## Project Structure

```
src/
├── app/
│   ├── home/
│   │   ├── home.component.ts
│   │   ├── home.component.html
│   │   └── home.component.scss
│   ├── app.component.ts
│   └── app.routes.ts
├── assets/
│   └── logo-icon-red-transparent.svg
├── index.html
├── main.ts
└── styles.scss
```

## Features

- Standalone Angular components
- Angular Material UI components
- Responsive design
- Smooth scrolling navigation
- Modern gradient theme with CSS variables

## Notes

- The logo file is located at `src/assets/logo-icon-red-transparent.svg`. You can replace it with your actual logo.
- The application uses Angular Material for UI components.
- All styling uses CSS custom properties (variables) defined in `src/styles.scss`.
