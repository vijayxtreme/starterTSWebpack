Tooling sucks:
Refer here: https://webpack.js.org/guides/typescript/

To start dev, just use npm start, then edit the src/ts files to do stuff
For production, npm build

If you want to build from scratch:
npm init -y
npm install webpack webpack-cli webpack-dev-server typescript ts-loader lodash @types/lodash 

Types lodash is important as lodash by itself is not an ES6 module, it has to be modularized for TS.

After that though, config your webpack.config.js to your heart's desire, along with tsconfig.json to recognize react, es6, etc (rather than using Babel)

Happy coding!

Also info on React config w/TS here:
https://www.typescriptlang.org/docs/handbook/react-&-webpack.html