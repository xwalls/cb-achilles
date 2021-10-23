# Description

The current project has a build error when running the command `npm run storybook`. Identify and fix the error such that Storybook starts successfully and displays the one story currency written.

Subject | Detail
------ | -------
Bounty | 20 ADA (Cardano)
Subjects | CSS, Svelte, MaterialUI
Languages | TS, JS, CSS, SCSS
Tools | npm, storybook, rollup

# Acceptance Criteria

- When the command `npm run dev` is run; Then the application builds without errors (deprecation warnings allowed).
- When the command `npm run storybook` is run; Then the storybook application builds and runs without errors and the `Components/TextInput` story is available in a browser.

## Documentation

- [Svelte](https://svelte.dev/docs)
- [MaterialUI for Svelte](https://sveltematerialui.com/)
- [Storybook for Svelte](https://storybook.js.org/blog/storybook-for-svelte/)

## Clues

- [Storybook and Webpack](https://storybook.js.org/docs/react/configure/webpack)
- [Storybook and PostCSS](https://storybook.js.org/addons/@storybook/addon-postcss)

# Development

1. Install the dependencies.
```bash
npm install
```
2. Attempt to start Storybook.
```bash
npm run storybook
```
3. View error in console output.