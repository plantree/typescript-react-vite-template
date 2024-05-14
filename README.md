# typescript-react-vite-template

An easy start for writing a React project with TypeScript based on Vite.

## How to use

1. Create your project based on this template.
    - Click `Use this template` in this page to create a new repository.
    - Use `git submodule`.

2. Update meta-information.
    - Update the `package.json`.
    - Change the author in `LISCENSE`.
    - Clean up this README.

3. Run
    - `npm install -g pnpm` (install `pnpm` firstly)
    - `pnpm install`
    - `npm run dev`: start the development server on `localhost:6543`

4. Testing
    - Unit tests:
        - `npm run test`: run unit tests with Jest and React Testing Library
    - End-to-end tests:
        - `npm run dev`: start the development server
        - // TODO

5. Linting
    - `npm run lint`: run linter
    - `npm run lint:fix`: fix lint issues

6. Continuous integration
    - Add `.yml` under `.github/workflows`

## Tech stack

- [TypeScript](https://www.typescriptlang.org)
- [ESLint](https://eslint.org) and [Prettier](https://prettier.io) already configured with the [🤏 Codely's configuration](https://github.com/CodelyTV/eslint-config-codely)
- [Jest](https://jestjs.io) with [React Testing Library](https://testing-library.com/docs/react-testing-library/intro) for the unit tests
- [GitHub Action Workflows](https://github.com/features/actions) set up to run tests and linting on push

## Reference

1. [typescript-react_best_practices-vite_template](https://github.com/CodelyTV/typescript-react_best_practices-vite_template) 