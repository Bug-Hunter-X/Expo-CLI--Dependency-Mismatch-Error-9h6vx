# Expo CLI Dependency Mismatch

This repository demonstrates a common error encountered when using the Expo CLI: dependency mismatch between the `package.json` and installed packages.  The error manifests as unexpected behavior or crashes during development.

## Problem
The `expoBug.js` file will throw an error if the dependencies are mismatched. This can occur when manually adding or removing dependencies without updating the `package.json` or node_modules using `npm install` or `yarn`.