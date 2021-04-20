# Webpack Basics Tutorial

Webpack basic code.

## Key notes:
- `./src/index.js` is the default entry point.
- `./dist/main.js` is the default minified js.
  
## Webpack commands used:
```
npx webpack --help
npx webpack --entry ./src/js/app.js  # giving the entry point.
npm run build # do same as of above command
```

## Tips:

- When installing a package that will be bundled into your production bundle, you should use `npm install --save`. If you're installing a package for development purposes (e.g. a linter, testing libraries, etc.) then you should use `npm install --save-dev`
- `npx` is node package execute. With npx we can execute a node package directly.

