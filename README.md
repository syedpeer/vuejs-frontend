# Vue Frontend UI

> Admin dashboard based on paper dashboard UI template + vue-router

This project is a vue version of [Paper-dashboard](https://www.creative-tim.com/product/paper-dashboard)
designed for vue js.The dashboard includes vue-router and vuex

![](http://i.imgur.com/3iC1hOs.gif)

## Build Setup

### install dependencies
`npm install`
### serve with hot reload at localhost:8080
`npm run dev`
### build for production with minification
`npm run build`
### run unit tests
`npm run unit`
### run and watch unit tests
`npm run unit:watch`

## Contribution guide
* `npm install` or `yarn install`
* If you use 3rd party libraries/components in more than 1 place make sure to define them globally for ease of use
  Example
  ```js
  Object.defineProperty(Vue.prototype, '$Chartist', {
    get() {
      return Chartist;
    }
  });
  ```