<h3 align="center">GH Prep Scholar</h3>

## About

`GH-Prep-Scholar` is a platform that allows low-income yet ambitious Ghanaian high school students effectively navigate the US undergrad college application process.


## Usage

Be sure to have [Node.js](https://nodejs.org/) installed before proceeding. **I recommend using Node's LTS releases, which is currently at v16.x. We only test our compiled CSS against v16.**

```shell
# Clone the repo
git clone https://github.com/fhylinjr/GH-Prep-Scholar
cd bootstrap-npm-starter

# Install dependencies
npm i

# Compile Sass
npm run css-compile

# Start server and watch Sass
npm start

# Watch Sass for changes (uses nodemon)
npm run watch

# Start local server
npm run server

# Watches Sass for changes and starts a local server
npm start
```

For the most straightforward development, open Terminal and run `npm start`.

Open <http://localhost:3000> to see the page in action.

## Scripts

The following npm scripts are available in this repo. With the exception of `npm start` and `npm test`, the remaining scripts can be run from your command line with `npm run scriptName`.

| Script | Description |
| --- | --- |
| `server` | Starts a local server (<http://localhost:3000>) for development with live reloads |
| `watch` | Automatically recompiles CSS as it watches the `scss` directory for changes |
| `css` | Runs `css-compile` and `css-prefix` |
| `css-compile` | Compiles source Sass into CSS |
| `css-lint` | Runs [Stylelint](https://stylelint.io) against source Sass for code quality |
| `css-prefix` | Runs [Autoprefixer](https://github.com/postcss/autoprefixer) on the compiled CSS |
| `css-purge` | Runs [PurgeCSS](https://purgecss.com) to remove CSS that is unused by `index.html` |
| `test` | Runs `css-lint` and `css`, in sequential order |
