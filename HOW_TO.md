# How to use stylus with create-react-app

This will require two dependencies, and some lines added to your `package.json` and it's super fast.

1. Create an app wih create-react-app.
2. Install `stylus` and `npm-run-all`.
4. Create your styl files inside `src/styl`.
5. Add a new script to package json that will watch the file, process sass and compile it into `src/css`.
6. Include the compiled css into React via `import`, this way your app will reload whenever the new css is compiled.
7. ran the new script along with `npm start`.

Ta da!
