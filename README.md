# Getting Started
-----------------------------------

This project is written in ES6 and SASS. 
Source data is in `src` directory.
Distribution data is in `dist` directory;

 - You can use static data from `dist` directroy to view/test app, without API server.

 - Recomended way to test is to use provided tools:

```shell
npm install
```

Post install script will run `grunt start` which will open app on `http://localhost:3000`
Mock API server will run on `http://localhost:3003`

# Data
-----------------------------------

1. Initial data 

Initial data is retrieved from Mock API server. If server is not used, data is read from `initialData.js` module. If JavaScript is disabled initial HTML is used.

2. Storing data

Since there is no real server, data is stored in `HTML5 LocalStorage`. On page reload data from LocalStorage is used.

3. Server

Node mock server is used as API server. You can change relevant responses on `http://localhost:3003`, eg 'post error'.

HINT: Click logo to reset initial state.


# Short intro:
-----------------------------------

- HTML / HTML5
	- W3C valid
	- Semantic markup
	- ARIA
	- LocalStorage
	- Accessible
- JS / ES6
	- Webpack
	- Babel
	- Uglify
	- ESlint
	- jQuery
- CSS / SASS	
	- node-sass
	- postcss
	- autoprefixer
	- cssnano
- SERVER / API
	- browser-sync
	- node-mock-server
- BROWSERS / DEVICES
	- Tested on IE9, Chrome, Firefox and Safari (latest), but it should work on any browser.
	- Responsive
	- Mobile first
	- Retina ready	

# Software
-----------------------------------

 - Chrome PixelPerfect plugin (PerfectPixel by WellDoneCode)
 - Pixlr, PhotoShop CS2
 - Sublime Text 3, IntelliJ
 - NodeJS

# Steps:

## 1. Initial setup:
-----------------------------------

- Directory structure

```
- src/
 - js/
 - scss/
 - images/
 index.html
```

- Installing tools
- Adding allowed plugins: jQuery

## 2. Configuration
-----------------------------------

- Webpack config
	- Babel
	- Uglify
	- ESlint extending "standard" rules
	- jQuery in separate bundle

- Grunt tasks
	- Copy
	- Sass
	- Postcss
	- Watch
	- Serve
	- Webpack
	- Mock server

## 3. Application
-----------------------------------

- js
	- main init
	- modules
	- helpers
	- constants
- scss
	- partials
	- mixins

## 4. Env
-----------------------------------
 - Dev
 - Prod


## 5. Grunt tasks
-----------------------------------
 - `grunt build`
 - `grunt build:prod`
 - `grunt start` - default: build dev files and open server + watch, browsersync, mock api server
 - `grunte start:prod` - build prod files and open server


