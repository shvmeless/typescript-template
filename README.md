# TypeScript Template

Custom template for **NodeJS** development using **TypeScript**.

**Initialization**

Modify the `package.json`, the `LICENSE`, and this `README.md` before start developing your project.

**TypeScript**

The configuration is available in the `./tsconfig.json` file.

- The root directory is set to `./src`.
- The output directory is set to `./dist`.
- The module type is set to `CommonJS`.
- The JavaScript version is set to `ES2022`.
- Generates `*.d.ts` and `*.js.map` files.

**Run the code without build:**

Use the `$ npm run dev` and `$ npm run dev:watch` scripts to run the code without build, or use the `$ npx ts-node-dev` command directly.

Also, the `./.vscode/launch.json` file contains a basic setup for debugging the code using **Visual Studio Code** tools.
