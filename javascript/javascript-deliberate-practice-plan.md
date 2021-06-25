# JavaScript Deliberate Practice Plan

## Goals
- Fluent in ES5/ES6 and apply best practices
- Able to start tackling full stack apps using just JavaScript

## ES5
### INPUT: ES5 Features
- js modules  
https://24ways.org/2014/javascript-modules-the-es6-way/  
https://medium.com/@crohacz_86666/basics-of-modular-javascript-2395c82dd93a  
https://www.intricatecloud.io/2020/02/creating-a-simple-npm-library-to-use-in-and-out-of-the-browser/  
https://medium.com/@thejasonfile/a-simple-intro-to-javascript-imports-and-exports-389dd53c3fac  
https://krasimirtsonev.com/blog/article/javascript-library-starter-using-webpack-es6  
https://app.pluralsight.com/library/courses/javascript-module-fundamentals/table-of-contents  
https://web.archive.org/web/20120826205255/http://blog.brianbeck.com/post/10667967423/node-js-require-in-the-browser  
https://tylermcginnis.com/javascript-modules-iifes-commonjs-esmodules/  
  - module formats and module loaders  
  https://www.davidbcalhoun.com/2014/what-is-amd-commonjs-and-umd/  
  https://dev.to/iggredible/what-the-heck-are-cjs-amd-umd-and-esm-ikm  
  https://www.jvandemo.com/a-10-minute-primer-to-javascript-modules-module-formats-module-loaders-and-module-bundlers/  
  es6 modules
  - Node modules  
  CommonJS - https://blog.risingstack.com/node-js-at-scale-module-system-commonjs-require/, https://itnext.io/deep-dive-into-node-js-module-architecture-b80fbd22dacb				
  - Module bundlers  
  Browserify  
  Webpack
- closures
  - JS closures
    - https://developer.mozilla.org/en-US/docs/Web/JavaScript/Closures
    - https://www.codingame.com/playgrounds/6516/closures-in-javascript-for-beginners
    - https://medium.com/javascript-scene/master-the-javascript-interview-what-is-a-closure-b2f0d2152b36
    - https://javascript.info/closure
  - C# closure
    - https://web.archive.org/web/20150707082707/http://diditwith.net/PermaLink,guid,235646ae-3476-4893-899d-105e4d48c25b.aspx
    - https://csharpindepth.com/articles/Closures
  - Closure Theory
    - https://martinfowler.com/bliki/Lambda.html
- Event loop
  - https://developer.mozilla.org/en-US/docs/Web/JavaScript/EventLoop
  - https://medium.com/front-end-weekly/javascript-event-loop-explained-4cd26af121d4
  - https://flaviocopes.com/javascript-event-loop/
  - 
- JavaScript Testing
  - https://wanago.io/2018/09/17/javascript-testing-tutorial-part-four-mocking-api-calls-and-simulating-react-components-interactions/  
  - https://michael-kuehnel.de/api/2016/11/04/data-mocking-ways-to-fake-a-backend-api.html  
- Debugging JS
  - https://hackernoon.com/please-stop-using-console-log-its-broken-b5d7d396cf15
  - https://blog.angular-university.io/javascript-debugging-tips-using-chrome-dev-tools-deb-js-and-more/
  - use watches in dev tools
    - https://stackoverflow.com/questions/47127260/debugging-with-console-log-is-there-shorthand-to-output-a-variable-and-its-valu
    - https://developers.google.com/web/tools/chrome-devtools/javascript/watch-variables
- Functional Programming
  - https://www.youtube.com/watch?v=sCAR8ZPM6ew&t=1787s

### OUTPUT: ES5 Demos
- strict mode
- hoisting
- closures
- IIFEs
- this, assign() / bind() / call() / apply() - https://medium.com/@omergoldberg/javascript-call-apply-and-bind-e5c27301f7bb
- constructor function
- prototypal inheritance
- `window` is global scope / variable in browsers (cf. Node.js)
- es5 modules (in the browser) with a module bundler
- https://jscomplete.com/learn-javascript

### OUTPUT: ES5 Basic Physics Demos
- basic particles

## ES6
### INPUT: Rapid ES6 Training
- https://www.pluralsight.com/courses/rapid-es6-training
- arrow / lambda functions
  - https://www.vinta.com.br/blog/2015/javascript-lambda-and-arrow-functions/
- class
  - https://medium.com/@luke_smaki/javascript-es6-classes-8a34b0a6720a
- Reactive programming
  - https://gist.github.com/staltz/868e7e9bc2a7b8c1f754
  - https://samueleresca.net/reactive-programming-damn-it-is-not-about-reactjs/
  - https://www.reddit.com/r/javascript/comments/6xcqpl/noob_question_is_reactive_programming_like_in/
  - https://www.pluralsight.com/courses/7f022dab-7de2-481e-8968-8916a1c24d9d
- testing
  - unit testing
    - mocking fetch requests
      - https://medium.com/@luke_smaki/javascript-es6-classes-8a34b0a6720a

### OUPUT: ES6 Demos - feature demos (using React/Node)
- modules, imports, exports
  export/import primitive values, functions, objects
- source maps
  webpack
- arrow / lambda functions
  create arrow functions in a module
- default parameters
  create function / arrow function with default parameters
- rest/spread
  handle function parameters using rest/spread
- object literal extensions
- for...of loop
  implement iteration using for...of
- template literals
  use strings using template literals
- destructuring
- class
  create classes
  create class hierachy

- iterator, generator
- input events
  create input event handlers
- promises
  handle async calls with Promise object
- debouncing
  create debouncer

## React
### OUTPUT: ReactDemos: Common Web app functionality
- Unit testing & TDD with Jest
- Async HTTP requests
- TBC...

## OUTPUT JS Exercises
- https://exercism.io/my/tracks/javascript
- https://js.checkio.org/

## Literature
- JavaScript: The Good Parts
- Eloquent JavaScript - https://eloquentjavascript.net/
- The JS Way - https://github.com/thejsway/thejsway
- Crockford on JavaScript (video series) - https://www.youtube.com/playlist?list=PL7664379246A246CB
