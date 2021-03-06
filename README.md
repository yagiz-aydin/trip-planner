### How to start TRIP PLANNER

- Install `npm install`
- Start `npm start `
- Build `npm run build `
- Running on `http://localhost:8080/`

### Project structure

```
build/
src/
|- index.jsx _______________________________ # Application entry
|- App.jsx _________________________________ # Application init
|  |- agent/index.jsx  # Requests & Response
|  |- Common/ #Images, Global & OverrideScss
|  |- Components/
|  |- Containers/
|  |- Provider/ #Context, Provider, Consumer
|  |- Utils/ #Helper Functions
|  |- Resources/ #API Connection

webpack
|- paths.js ________________________________ # webpack paths needed
|- webpack.common.js _______________________ # common webpack config
|- webpack.dev.js __________________________ # development config
|- webpack.prod.js _________________________ # production config
```

### Technologies

- [Webpack 4](https://github.com/webpack/webpack)
- [Babel 7](https://github.com/babel/babel) [ transforming JSX and ES6,ES7,ES8 ]
- [React](https://github.com/facebook/react) `16.8`
- [Lodash](https://github.com/lodash/lodash)
- [Jest](https://github.com/facebook/jest) [ Unit test]
- [Enzyme](http://airbnb.io/enzyme/) for UI testing.
- [Eslint](https://github.com/eslint/eslint/) with airbnb config
- [Prettier](https://github.com/prettier/prettier) [ Code formatter ]
- [Style](https://github.com/webpack-contrib/style-loader) & [CSS Loader](https://github.com/webpack-contrib/css-loader) & [SASS-loader](https://github.com/webpack-contrib/sass-loader)
- [CSS modules](https://github.com/css-modules/css-modules) [ Isolated style based on each component ]
- [Browsers list](https://github.com/browserslist/browserslist) [ Share target browsers between different front-end tools, like Autoprefixer, Stylelint and babel-preset-env ]
- [React hot loader](https://github.com/gaearon/react-hot-loader)
- [Webpack dev serve](https://github.com/webpack/webpack-dev-server)

## For this project

- [React-Router](https://reactrouter.com/web/guides/quick-start)
- [Semantic-UI-React](https://react.semantic-ui.com/)
