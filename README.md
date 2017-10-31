ES2015 Modules in Browser
========================

* Run: Start a Webserver in `dist/` folder
* Open the `index.html` via the web server
* Check the console for **Hello, World** message

Current Browser Support: http://caniuse.com/#feat=es6-module

Notes
-----
* Make sure, you set `module` to `es2015` in your `tsconfig.json`
* Your import statements must end with `.js` otherwise the imported file cannot found by your browser (https://github.com/Microsoft/TypeScript/issues/16577)


