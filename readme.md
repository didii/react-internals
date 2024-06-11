# Vite + React + TypeScript + ESLint + Prettier

Some template I built up, this includes:

* [Vite](https://vitejs.dev/): The build tool
* [React](https://react.dev/): The FE framework
* [TypeScript](https://www.typescriptlang.org/): The main programming language
* [ESLint](https://eslint.org/): linter to help writing consistent code
* [Prettier](https://prettier.io/): formatter to speed up development and prevent annoying merge conflicts

## Tooling

I recommend VSCode with the following extensions in order of importance:

* [Format Code Action](https://marketplace.visualstudio.com/items?itemName=rohit-gohri.format-code-action): Allows the command `source.formatDocument` in the `editor.codeActionsOnSave` so we can specify the order in which these occur
* [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint): Show ESLint errors
* [Code Spell Checker](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker): Simple and effective spell checker
* [Error Lens](https://marketplace.visualstudio.com/items?itemName=usernamehw.errorlens): Show errors and warnings inline

## ESLint

ESlint has a big configuration file included.
The main goal of this is to have it behave as a helpful tool rather than an annoyance.
Most errors are set to warnings and everything that TS already tells us, is turned off.

Included plugins:

* React: adds some helpful warnings here and there like forgetting a `key` attribute inside a `map`
* React-hooks: probably the most important one to make sure your dependency array is up-to-date. Never ignore that rule unless you know what you are doing.
* Prettier: removes all formatting rules from eslint since this is prettier's job

Have fun!
