# CI/CD Playground

Hands-on project for learning GitHub Actions on a React + Vite application.

## Features

- GitHub Actions workflow (lint, build)
- React + TypeScript sample app

## Tech Stack

- Vite
- React
- TypeScript
- GitHub Actions

## Getting Started

```bash
git clone https://github.com/ghostland-dev/github-actions-playground.git
cd github-actions-playground
cd vite-project
npm install
npm run dev
```

Other scripts:

- `npm run build`: tsc && vite build
- `npm run lint`: eslint . --ext ts,tsx --report-unused-disable-directives --max-warnings 0
- `npm run preview`: vite preview

## Deploy

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2Fghostland-dev%2Fgithub-actions-playground&root-directory=vite-project)

Click the button to deploy your own copy on Vercel in one step.

The app lives in the `vite-project` folder, which the button sets as the Vercel root directory.

## Author

**Ismail.M**, Software Engineer & DevOps

- GitHub: [@ghostland-dev](https://github.com/ghostland-dev)
- Website: [ismail-mouyahada.com](https://www.ismail-mouyahada.com)
