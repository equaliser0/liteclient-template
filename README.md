# ARK lite client Quick Start

## installation
1. install a recent version of NodeJS
2. clone this repository: `git clone https://github.com/arkecosystem/ark-liteclient-template`
3. install build components: `npm install -g browserify uglify-js watchify`
4. install dependencies: `npm install`
5. build the dependencies: `npm run build-dependencies`
6. build app.js: `npm run build`
7. open index.html in a browser

## develop your app
1. perform change in app.js and index.html
2. build the app `npm run build` (if you want to have it automated each time you save app.js: `npm run watch`)
3. refresh index.html in the browser



## deploy
Just copy `app.min.js` and `index.html` on your remote server and it works.
