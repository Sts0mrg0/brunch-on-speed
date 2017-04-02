# Brunch on Speed

This is a skeleton (or boilerplate) for [Brunch](http://brunch.io), a fast and easy to configure building tool for modern Web development. The skeleton is intended to be a foundation for a long-scroll, single, static Web page. 

## Installation

Clone this repo manually or use `brunch new DIRECTORY -s filter1/brunch-on-speed`

## Features
* [Twitter Bootstrap](http://getbootstrap.com)
* [jQuery](http://jquery.com)
* Compilation of ECMAScript 2015 (ECMAScript 6) files with [Babel](https://babeljs.io)
* Uglification and concatenation of Javascript files with [UglifyJS](http://lisperator.net/uglifyjs/)
* Extending CSS with [Sass](http://sass-lang.com)
* Autoprefixing, concatenation, minification (and more) of CSS files with [Pleeease (PostCSS)](http://pleeease.io)
* [ESLint](http://eslint.org) with [AirBnB Javascript Style Guide](https://github.com/airbnb/javascript)
* Auto reload of local Web server on file change
* index.html with all essential meta tags for SEO and Social Media

## Recommendation
To complete the development environment, I suggest the use of code linters in your favorite text editor. For [Sublime Text](http://www.sublimetext.com), I can recommend the following linters: [ESLint](https://github.com/roadhump/SublimeLinter-eslint), [Sass](https://github.com/attenzione/SublimeLinter-scss-lint) and [HTML](https://github.com/SublimeLinter/SublimeLinter-html-tidy).

## Getting started with Brunch

* Install (if you don't have them):
    * [Node.js](http://nodejs.org): `brew install node` on OS X
    * [Brunch](http://brunch.io): `npm install -g brunch`
    * Brunch plugins and app dependencies: `npm install`
* Run:
    * `npm start` — watches the project with continuous rebuild. This will also launch HTTP server with [pushState](https://developer.mozilla.org/en-US/docs/Web/Guide/API/DOM/Manipulating_the_browser_history).
    * `npm run build` — builds minified project for production
* Learn:
    * `public/` dir is fully auto-generated and served by HTTP server.  Write your code in `app/` dir.
    * Place static files you want to be copied from `app/assets/` to `public/`.
    * [Brunch site](http://brunch.io), [Getting started guide](https://github.com/brunch/brunch-guide#readme)
