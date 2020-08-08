# Next.js Starter Project

This is a boilerplate package that sets up a [Next.js](https://nextjs.org/) project for development with relevant tools and preferences.

## Getting Started

1. Clone the repository:

   ```
   git clone https://github.com/tobiasziegler/nextjs-starter [project-name]
   ```

1. Initialise your project with a clean Git repository:

   ```
   cd [project-name]
   rm -rf .git
   git init
   ```

1. Configure the npm package information for your project by editing fields in `package.json` (e.g., `name`, `description`, `author`).

1. Install the project's dependencies:

   ```
   npm install
   ```

   (NB: If you prefer to use `yarn`, you'll want to delete the `package-lock.json` file before running `yarn` to install dependencies.)

From here, you should be all set to fire up a code editor and start your new project!

## Features

- Code editor configuration using [EditorConfig](https://editorconfig.org/).
- JavaScript linting using [ESLint](https://eslint.org/) and code formatting using [Prettier](https://prettier.io/), applying the [Airbnb JavaScript Style Guide](https://github.com/airbnb/javascript).
- Formatting of other file formats using [Prettier](https://prettier.io/).
- Pre-commit hooks to lint and format staged files and automatically fix problems, using [Husky](https://github.com/typicode/husky) and [Lint-Staged](https://github.com/okonet/lint-staged).
- The project uses a `src` directory as added in [Next.js 9.1](https://nextjs.org/blog/next-9-1#src-directory-support), to contain the `pages` and any other source code directories.

## Licence

MIT
