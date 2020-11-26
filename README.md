# campania-fun

Implementation steps:

- npm init -y

- npm install webpack webpack-cli --save-dev

- in packaje.json: "build": "webpack"

- npm i @babel/core babel-loader @babel/preset-env @babel/preset-react --save-dev
preset-env to treanspile modern JS to ES5

-created .babelrc

- created webpack.config.js

- npm i react react-dom

- write  "private": true, // instead of "main": "index.js" to avoid accidental publish,

- I followed these instructions: https://www.valentinog.com/blog/babel/

- to solve the error: 
   Error: Cannot find module ‘webpack-cli/bin/config-yargs’, 
   I had to follow this instructions: https://medium.com/@cyishere/error-cannot-find-module-webpack-cli-bin-config-yargs-6d704533062a

- Load CSS: https://webpack.js.org/guides/asset-management/#setup

- followed this to get debbugable files into chrome dev tools: https://www.mikeglopez.com/source-mapping-webpack-for-chrome/

- caching from https://webpack.js.org/guides/caching/#extracting-boilerplate

- added sass and the loader: https://www.npmjs.com/package/sass-loader

