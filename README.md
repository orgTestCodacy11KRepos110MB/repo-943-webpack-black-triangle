# webpack-black-triangle

A minimal, development-focussed template to get you up and running with Webpack, Babel & LESS.

Read how it works at [jamesknelson.com](http://www.jamesknelson.com).

**Things it does**:

- Makes ES6 "just work"
- Compiles and includes your LESS files
- Serves your files
- Automatically recompiles/reloads your page when JavaScript/LESS files change
- Decide where your files go (to a degree)

**Things it doesn't do**:

- Handle your deployment build
- Include any runtime dependencies (other than babel's polyfill)

## Install with three lines

Just `git clone` & `npm install`:

```
git clone https://github.com/jamesknelson/webpack-black-triangle.git
npm install webpack-dev-server -g
npm install
```

## Then use it

Run the dev server:

```
webpack-dev-server
```

Then open [localhost:8080](http://localhost:8080/).

## Why a black triangle?

Because [this](http://rampantgames.com/blog/?p=7745).
