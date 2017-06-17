Starter - Webpack 2 | sass | live reload | ES6
================================================================================

Overview
--------------------------------------------------------------------------------

An easy place to start your vanilla JS project. Includes all you need to get up and running with Webpack looking after compiling and bundling of all your assets including Sass and ES6.

Getting up and running
--------------------------------------------------------------------------------

1. clone repo
2. run `npm install` to install all dependencies
3. run `npm run webpack` to package and compile all your files, or
4. run `npm run dev` to run webpack-dev-server with live relaoding at localhost:8080

What next?
--------------------------------------------------------------------------------

All you need to get started is in the /src folder:
- index.html is your main template file, you don't need to worry about adding links/refs to your scripts or styles, webapck does that automatically
- js/main.js is your starting place for all your scripting goodness. For maintainablilty it's nice to break yout code into individual scripts and reference them here (as is done with the example app.js)
- styles/main.scss is your starting place for all Sassy styles. Again, probably nicest to break your style sheets into smaller files and import them here