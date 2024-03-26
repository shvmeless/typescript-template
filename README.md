# TypeScript Template

Custom template for **NodeJS** development using **typescript**.

## Eslint

The **eslint** configuration in this project extends from the `@shvmerc/eslint-config` library. The **eslint** configuration is available in the `./eslintrc` file.

To execute the analysis run `$ npm run lint`.

## TypeScript

The **TypeScript** configuration is available in the `./tsconfig.json` file.

Some of the default settings are:

* The root directory is set to `./src`.
* The output directory is set to `./dist`.
* The module type is set to `CommonJS`.
* The JavaScript version is set to `ES2022`.
* Generates `*.d.ts` and `*.js.map` files.

## Code Execution

Use the `$ npm run dev` and `$ npm run dev:watch` scripts to run the code without build, or use the `$ npx ts-node-dev` command directly.

Also, the `./.vscode/launch.json` file contains a basic setup for debugging the code using **Visual Studio Code** tools.

## Projects

Remember to modify the `package.json`, the `LICENSE`, and this `README.md` before starting a new project.
