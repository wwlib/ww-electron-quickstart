# ww-electron-quickstart

This is a simple quick start using ES6 running in Electron (formerly atom-shell).

To get it running on a Mac via the terminal:

```
Make sure iojs is installed (for npm)
https://iojs.org/en/index.html

# Install electron (formerly atom-shell) globally in your $PATH
npm install electron-prebuilt -g
(May require: sudo npm install electron-prebuilt -g)

# From inside the project directory..
npm install

# Build
gulp
(ctrl-c when it is done to return to the shell)

# Run
electron .
```

## Gulp
The included Gulp script will transpile the ES6 using Babel into the dist folder. It will also generate sourcemaps to make debugging easier (using Chrome's dev tools).

## Electron
https://github.com/atom/electron/tree/master/docs
