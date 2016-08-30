# Getting Started

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

1. Initial data 

Initial data is retrieved from Mock API server. If server is not used, data is read from `initialData.js` module. If JavaScript is disabled initial HTML is used.

2. Storing data

Since there is no real server, data is stored in `HTML5 LocalStorage`. On page reload data from LocalStorage is used

HINT: Click logo to reset initial state.



-----------------------------------
# 0. Tools list:
-----------------------------------
- HTML / HTML5
	- Semantic markup
	- ARIA
	- LocalStorage
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

# Steps:

-----------------------------------
# 1. Initial setup:
-----------------------------------

## Directory structure

```
- src/
 - js/
 - scss/
 - images/
 index.html
```

## Entry js/scss files

```
- js/
 main.js
- scss/
 style.scss
 ```

## Project init
 Creating `project.json`

`npm init`

## Installing tools

- assets
	- copy	
- js
	- Webpack
	- Babel
	- Uglify
	- ESlint
- sass	
	- node-sass
	- postcss
	- autoprefixer
	- cssnano
- serve
	- browser-sync
	- watch
- API
	- node-mock-server	

## Adding allowed plugins

- jQuery

-----------------------------------
# 2. Configuration
-----------------------------------

- Webpack 
	- entry/output
	- Babel
	- Uglify
	- ESlint
	- jQuery in separate bundle

- Grunt
	- Copy
	- Sass
	- Postcss
	- Watch
	- Serve
	- Webpack
	- Mock server

-----------------------------------
# 3. Application
-----------------------------------

- js
	- main init
	- modules
- scss
	- partials

-----------------------------------
# 4. Software
-----------------------------------
 - Chrome PixelPerfect plugin (PerfectPixel by WellDoneCode)
 - Pixlr, PhotoShop CS2
 - Sublime Text 3, IntelliJ

-----------------------------------
# 5. Env
-----------------------------------
 - Dev
 - Prod

 -----------------------------------
# 6. Grunt tasks
-----------------------------------
 - `grunt build`
 - `grunt build:prod`
 - `grunt start` - build dev files and open server + watch, browsersync, mock api server
 - `grunte start:prod` - build prod files and open server


