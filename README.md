# generator-web [![Build Status](https://secure.travis-ci.org/gilbarbara/generator-web.png?branch=master)](https://travis-ci.org/gilbarbara/generator-web) [![Built with Grunt](https://cdn.gruntjs.com/builtwith.png)](http://gruntjs.com/)

Web generator

Build a modern website with h5bp, bootstrap 3, jquery (and modernizr, underscore, Font Awesome).
Uses bower for dependencies and grunt for tasks.

View the initial page: (http://gilbarbara.github.io/generator-web/)

## Features

* Built-in preview server with LiveReload
* Automagically compile Sass
* Automagically concatenate, lint and compress your scripts
* Optional - Modernizr builds
* Optional - Underscore.js
* Optional - Font Awesome
* Optional - Respond.js (for IE8)
* Optional - html5shiv (for IE8)

For more information on what `generator-web` can do for you, take a look at the [Grunt tasks](https://github.com/gilbarbara/generator-web/blob/master/app/templates/_package.json) used in our `package.json`.

## Getting Started

- Install: `npm install -g generator-web`
- Run: `yo web AppName`
- Run `grunt serve` for preview


## Options

* `--skip-install`

  Skips the automatic execution of `bower` and `npm` after scaffolding has finished.

## License

[MIT License](http://en.wikipedia.org/wiki/MIT_License)

[![NPM](https://nodei.co/npm/generator-web.png?compact=true)](https://nodei.co/npm/generator-web/)
