# ts-course-proj-2

A small React + TypeScript project scaffolded with Create React App. It includes a set of reusable components, a mock data module, and a simple build/deploy setup for GitHub Pages.

## Project Overview

- Purpose: a searchable user/profile demo built with React and TypeScript.
- Key tech: React 18, TypeScript, SASS, generate-react-cli for component generation.

## Quick Start

Prerequisites:

- Node.js (14+ recommended)
- Yarn or npm

Install dependencies:

```bash
npm install
# or
yarn
```

Run the development server:

```bash
npm start
```

Build for production:

```bash
npm run build
```

Deploy to GitHub Pages:

```bash
npm run deploy
```

Generate a new component (uses `generate-react-cli`):

```bash
npm run component -- ComponentName
```

See the project's scripts in [package.json](package.json).

## Project Structure

- `public/` — static HTML and metadata (entry [public/index.html](public/index.html)).
- `src/` — application source code
  - `src/index.tsx` — app entry point ([src/index.tsx](src/index.tsx))
  - `src/App.tsx` — main app component ([src/App.tsx](src/App.tsx))
  - `src/components/` — UI components (e.g. `Button`, `Search`, `UserCard`)
  - `src/mock/` — mock data used by the app
  - `src/utils/` — helper utilities and type guards

- `build/` — generated production build (output of `npm run build`)

## Notes on Development

- Styles are written using SCSS modules alongside components.
- Component generator helps scaffold new components quickly using the existing conventions.

## Contributing

Contributions are welcome. Open an issue or submit a pull request with a clear description of your changes.

## License

This project is provided under the MIT License. Replace or update this notice as needed.

---

If you'd like, I can also:

- add an example screenshot or preview in `README.md` (ask me to include images from `build/`)
- expand the `Contributing` section with a pull-request checklist
- add CI instructions (GitHub Actions) for build + deploy
# TypeScript курс. Проект GitHub user finder
