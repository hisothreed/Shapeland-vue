# Shapeland-vue

Interactive Canvas implementation with Vuejs.


![Example](https://imgur.com/a/f7Wzs)

## Usage

First Clone The Repo: 

``` bash

git clone 

```
To get it up and running, run:

``` bash
# first install dependencies
npm install

# then serve with hot reload at localhost:8080
npm run dev

```

#Features 

* Draggable components.
* shape rendering and manipulation (type, color, size, scale, text) on a single canvas.

## Tests

Vuejs automated tests.

### Running Unit Test

Vuejs TDD With Jest and vue-test-utils.
It will run several tests to make sure events, emits, props, and data are all in place and reactive to each other,
working as it suppose to.

``` bash

npm run unit


```

### Running Code Style Test

Vuejs eslint will make sure that the code doesn’t adhere to Airbnb js style guide.

``` bash

# it will run automatically when serving with hot reload, see Usage

# or you can run it separately with the command below

npm run lint

```

## Building The App 

``` bash
# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report
```


## Built With 
* Vuejs
* Webpack
* vue-draggable
* Babel/ES6
* ESlint
* Jest Testing framework
* vue-test-utils
