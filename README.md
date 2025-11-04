# CI Node Example - GitHub Actions

## What this contains
- Simple Express app (`index.js`)
- Basic Jest test (`tests/app.test.js`)
- `package.json` with scripts: start, test, build
- GitHub Actions workflow: `.github/workflows/ci.yml`
- `.gitignore`

## How to run locally in Visual Studio / VS Code
1. Extract the ZIP and open the folder in Visual Studio or VS Code.
2. Install Node.js (v18+) and npm.
3. In a terminal: `npm install`
4. Run the app: `npm start`
5. Run tests: `npm test`

## About the CI workflow
The provided workflow runs on pushes to `main`, installs Node 18, runs `npm install`, runs tests, and runs the build step (if present).
