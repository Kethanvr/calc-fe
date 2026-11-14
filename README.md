# calc-fe

A React and TypeScript frontend experiment built with Vite. The current home screen combines a drawing canvas with LaTeX typesetting, using MathJax for rendered expressions.

## Run locally

Requirements: Node.js and npm.

```bash
npm install
npm run dev
```

Open the local address printed by Vite. To create a production bundle, run `npm run build`; the output is written by Vite.

## Project layout

- `src/screens/home/`: main screen
- `src/components/`: reusable interface components
- `src/lib/` and `src/constants.ts`: supporting code and configuration

This is a frontend prototype; the repository does not document a backend service.
