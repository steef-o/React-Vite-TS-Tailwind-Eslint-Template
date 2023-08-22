# React + Vite + TypeScript + TailwindCSS Template

This is a template for creating React applications using Vite as the build tool, TypeScript for type-checking, and TailwindCSS for styling. I've developed this template primarily for my own use, but it's available for anyone looking for a solid starting point for their React projects.

Please note that this template comes with an opinionated ESLint configuration to ensure code consistency and quality. However, you are free to customize it according to your preferences and project requirements.

Also note that this README.md file is written by Chat-GPT3.5, so it may not be entirely accurate.
## Features

- **React:** A popular JavaScript library for building user interfaces.
- **Vite:** A fast build tool that aims to provide near-instantaneous development server startup and quick building.
- **TypeScript:** A typed superset of JavaScript that compiles to plain JavaScript.
- **TailwindCSS:** A utility-first CSS framework for rapidly building custom designs.
- **ESLint:** A pluggable linting utility for JavaScript and TypeScript.
- **Prettier:** An opinionated code formatter to enforce consistent code style.
- **Vitest:** A test runner for Vite projects.

## Getting Started

1. Clone this repository: `git clone <repository-url>`
2. Navigate to the project folder: `cd react-vite-ts-tailwind-eslint-template`
3. Install dependencies: `npm install`
4. Run the development server: `npm run dev`

Open your browser and visit [http://localhost:3000](http://localhost:3000) to see your app in action.

## Available Scripts

- `npm run dev`: Starts the development server.
- `npm run build`: Builds the production-ready app.
- `npm run preview`: Serves the production build locally for preview.
- `npm test`: Runs tests using Vitest.

## Hosting

I recommend using [Vercel](https://vercel.com/) for hosting your React + Vite applications. It's easy to set up and provides a seamless deployment experience. You can deploy your app to Vercel by following these steps:

1. Install the Vercel CLI: `npm install -g vercel`
2. Navigate to your project folder: `cd react-vite-ts-tailwind-eslint-template`
3. Run `vercel login` to log in to your Vercel account.
4. Run `vercel` and follow the prompts to deploy your app.

or go to [Vercel](https://vercel.com/docs/frameworks/vite) and import your project.

## Project Defaults

This template includes some default configurations to help you get started.
Everything can of course be modified to suit your needs.

### Vite Configurations
- Default port is `3000`
- Support for absolute paths with `vite-tsconfig-paths`
- Uses SWC for faster dev server.

## License

This project is licensed under the [MIT License](LICENSE).