To reproduce:
1. `yarn install`
2. `yarn build`
3. Serve the `dist` folder, e.g. `npx http-server dist/`
4. Check console: `Uncaught TypeError: Cannot redefine property: getFusedDyActivation`