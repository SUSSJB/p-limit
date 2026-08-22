# Architecture

## Summary
This project is a JavaScript application that benchmarks and limits the execution time of functions. It uses Node.js as its runtime environment.

## High-Level Module/Directory Layout
- **`recipes.md`**: Contains recipes or examples for using the benchmarking and limiting features.
- **`scripts`**: Contains scripts for running benchmarks and managing the build process.
  - `benchmarker.js`: A script for running benchmark tests.
  - `scripts/benchmarker.js`: Another script for benchmarking.
- **`scripts/benchmarker.js`**: The primary script for running benchmarks.
- **`scripts/index.js`**: Likely serves as the entry point for scripts.
- **`index.js`**: The main application file which handles the core functionality.
- **`index.test-d.ts`**: Test files for TypeScript definitions.
- **`index.d.ts`**: TypeScript definitions for the application.
- **`benchmark.js`**: Likely a utility file for benchmarking.
- **`index.js`**: Main application file in JavaScript.
- **`readme.md`**: Documentation for the project.
- **`recipes.md`**: Recipes or examples for using the application.
- **`license`**: License information for the project.

## Naming and Structural Conventions
- **Test Files**: Tests are typically placed in directories named after the module they test, e.g., `index.test-d.ts` for TypeScript tests of the `index.js` module.
- **Module Boundaries**: The structure suggests a clear separation between the main application (`index.js`), utilities (`benchmark.js`), and scripts for running tests (`scripts/*.js`).
- **File Extensions**: `.d.ts` files are used for TypeScript declarations, indicating that the project uses TypeScript with declaration files.

## Closing Note
New tickets are appended below this line as components are implemented.
## General
- **PRODPLIMIT-2** Implement isIdle getter — index.js (function pLimit; function limitFunction), index.d.ts (type LimitFunction; function pLimit; type Options; function limitFunction), test.js
