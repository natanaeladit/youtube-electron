# Electron

A basic Electron application needs just these files:

- `package.json` - Points to the app's main file and lists its details and dependencies.
- `main.js` - Starts the app and creates a browser window to render HTML. This is the app's **main process**.
- `index.html` - A web page to render. This is the app's **renderer process**.

## To Use

```bash
# Install dependencies
npm install
# Run the app
npm start
```

## To publish with electron-forge

```bash
npm install --save-dev @electron-forge/cli
npx electron-forge import
npm run make
```