<p align="center">
Заглушка для EXPANSE.BRANDS
<img src="/static/preview.jpg">
</p>
# Static HTML Webpack Boilerplate

## Features

- Write SCSS and modern JavaScript code in `src` and build minified, transpiled
  code for production in `dist`
- Continuous integration with linting tests and deploying to `gh-pages`
- Live reloading with webpack-dev-server
- ES6+ to ES5 transpilation, bundling, and minification
- SCSS to CSS transpilation, bundling, autoprefixing, and minification
- Automatic copying of HTML and static assets from `src` to `dist` folders
- Linting for styles and scripts

## Usage

- Write all your ES2015+ Javascript code in `src/js` and SCSS styling in
  `src/style`. Store static assets in `src/static`. Organize HTML files the way
  you like.
- Available commands:

  - `npm run build`: Build files to the `dist` folder. Transpiles down to ES5
    and bundles all JS into `app.bundle.js`. Transpiles SCSS to CSS and adds
    prefixing into `style.bundle.css`. Copies static assets and HTML over, and
    bundled CSS and JS gets added to HTML file.
  - `npm run start:dev`: Run `webpack-dev-server` at `localhost:9000`. Includes
    live reloading on any Javascript/SCSS/HTML changes.
  - `npm run start`: Builds files and runs a local production server on
    `localhost:8080` with `http-server`.
  - `npm run run lint:js`: Lints JS with ESLint.
  - `npm run lint:styles`: Lints SCSS stylesheets with stylelint.
  - `npm run lint:html`: Lints HTML for a11y issues using pa11y.
