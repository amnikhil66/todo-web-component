# ToDo List - Web Components

## Build a TODO application which satisfies the following the criteria:

1. User should be able to add, remove, update and preview a task
2. User should be able to mark and unmark a task as `Completed`
3. Persist the state of the ToDo List in an offline storage on the browser
4. The state of the ToDo list should be saved in a remote service

## Implementation Steps:

#### Step 1:
Complete frontend layer of the problem statement, which includes the first 3 statements of the above requirements.

#### Step 2:
Finally integrate the frontend layer with the backend service created to store the user's Todo list remotely, as explained in the last statement of the above requirements.

## Technical Requirements:

1. Should persist Todo state both offline and sync with an online service
2. Should be built purely using JavaScript, no restriction on the version of JavaScript
3. Should have a build system which will optimize the development and deployment process

## Mandatory Tech Requirements:

* Vanilla JavaScript
* [Web Components](https://developer.mozilla.org/en-US/docs/Web/Web_Components)
* Use of Sass/Less/Stylus is permitted to maintain styles (*optional*)
* Use some form of a Node build system, recommendation [Webpack](https://webpack.js.org/)
* Lite weight backend service, recommendation [Express](https://expressjs.com/), [Koa](https://koajs.com/)
* Lite weight storage solution, recommendation [SQLite](https://www.sqlite.org/index.html)

## Good to haves

* Remote hosting of the solution
* Capability to deploy static assets to an CDN

## Build System Requirements:

* Convert any ES6 and above code to ES5
* Convert any Sass/Less/Stylus to either css or JS induced styles
* Minify and uglify the output assets

## Permitted Helper Libraries:

* [Lodash](https://lodash.com/)
* [Axios](https://github.com/axios/axios) *or* [Fetch](https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API)

## Strict No-Nos

* No use of DOM selector or manupilation libraries will be allowed
* No use of CSS frameworks will be allowed