# api documentation for  [react-router-redux (v4.0.8)](https://github.com/reactjs/react-router-redux#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-react-router-redux.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-react-router-redux) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-react-router-redux.svg)](https://travis-ci.org/npmdoc/node-npmdoc-react-router-redux)
#### Ruthlessly simple bindings to keep react-router and redux in sync

[![NPM](https://nodei.co/npm/react-router-redux.png?downloads=true)](https://www.npmjs.com/package/react-router-redux)

[![apidoc](https://npmdoc.github.io/node-npmdoc-react-router-redux/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-react-router-redux_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-react-router-redux/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-react-router-redux/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-react-router-redux/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "authors": [
        "James Long",
        "Tim Dorr"
    ],
    "bugs": {
        "url": "https://github.com/reactjs/react-router-redux/issues"
    },
    "dependencies": {},
    "description": "Ruthlessly simple bindings to keep react-router and redux in sync",
    "devDependencies": {
        "babel-cli": "^6.1.2",
        "babel-core": "^6.7.4",
        "babel-eslint": "^7.1.1",
        "babel-loader": "^6.2.0",
        "babel-plugin-transform-es3-member-expression-literals": "^6.5.0",
        "babel-plugin-transform-es3-property-literals": "^6.5.0",
        "babel-polyfill": "^6.7.4",
        "babel-preset-es2015": "^6.3.13",
        "babel-preset-react": "^6.5.0",
        "babel-preset-stage-1": "^6.3.13",
        "babel-register": "^6.4.3",
        "eslint": "^3.15.0",
        "eslint-config-react-app": "^0.5.0",
        "eslint-plugin-flowtype": "^2.29.2",
        "eslint-plugin-import": "^2.2.0",
        "eslint-plugin-jsx-a11y": "^4.0.0",
        "eslint-plugin-react": "^6.8.0",
        "expect": "^1.13.0",
        "history": "^3.0.0",
        "isparta": "^4.0.0",
        "isparta-loader": "^2.0.0",
        "karma": "^1.4.1",
        "karma-coverage": "^1.1.1",
        "karma-firefox-launcher": "^1.0.0",
        "karma-mocha": "^1.3.0",
        "karma-mocha-reporter": "^2.2.2",
        "karma-sourcemap-loader": "^0.3.5",
        "karma-webpack": "^2.0.2",
        "mocha": "^3.2.0",
        "react": "^15.4.2",
        "react-dom": "^15.4.2",
        "react-redux": "^5.0.2",
        "react-router": "^3.0.0",
        "redux": "^3.0.4",
        "redux-devtools": "^3.0.0",
        "redux-devtools-dock-monitor": "^1.0.1",
        "redux-devtools-log-monitor": "^1.0.1",
        "webpack": "^2.2.1"
    },
    "directories": {},
    "dist": {
        "shasum": "227403596b5151e182377dab835b5d45f0f8054e",
        "tarball": "https://registry.npmjs.org/react-router-redux/-/react-router-redux-4.0.8.tgz"
    },
    "files": [
        "*.md",
        "dist",
        "LICENSE",
        "lib",
        "src"
    ],
    "gitHead": "a2825ac0b8e34662624455ab98e29e2eb27f8096",
    "homepage": "https://github.com/reactjs/react-router-redux#readme",
    "keywords": [
        "react",
        "redux",
        "router"
    ],
    "license": "MIT",
    "main": "lib/index",
    "maintainers": [
        {
            "name": "jlongster",
            "email": "longster@gmail.com"
        },
        {
            "name": "timdorr",
            "email": "timdorr@timdorr.com"
        }
    ],
    "name": "react-router-redux",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/reactjs/react-router-redux.git"
    },
    "scripts": {
        "build": "npm run build:commonjs & npm run build:umd & npm run build:umd:min",
        "build:commonjs": "mkdir -p lib && babel ./src -d lib",
        "build:umd": "webpack dist/ReactRouterRedux.js",
        "build:umd:min": "NODE_ENV=production webpack dist/ReactRouterRedux.min.js",
        "lint": "eslint examples src test",
        "prepublish": "npm run build",
        "test": "npm run lint && npm run test:node && npm run test:browser",
        "test:browser": "karma start",
        "test:cov": "npm run test:cov:browser && npm run test:cov:node && npm run test:cov:report",
        "test:cov:browser": "COVERAGE=true karma start",
        "test:cov:node": "babel-node $(npm bin)/isparta cover $(npm bin)/_mocha report --dir ./coverage/node-coverage -- --recursive ./test/node",
        "test:cov:report": "$(npm bin)/istanbul report --dir ./coverage --include **/*coverage.json html text",
        "test:node": "mocha --compilers js:babel-register --recursive ./test/*.spec.js"
    },
    "tags": [
        "react",
        "redux"
    ],
    "version": "4.0.8"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module react-router-redux](#apidoc.module.react-router-redux)
1.  [function <span class="apidocSignatureSpan">react-router-redux.</span>go ()](#apidoc.element.react-router-redux.go)
1.  [function <span class="apidocSignatureSpan">react-router-redux.</span>goBack ()](#apidoc.element.react-router-redux.goBack)
1.  [function <span class="apidocSignatureSpan">react-router-redux.</span>goForward ()](#apidoc.element.react-router-redux.goForward)
1.  [function <span class="apidocSignatureSpan">react-router-redux.</span>push ()](#apidoc.element.react-router-redux.push)
1.  [function <span class="apidocSignatureSpan">react-router-redux.</span>replace ()](#apidoc.element.react-router-redux.replace)
1.  [function <span class="apidocSignatureSpan">react-router-redux.</span>routerMiddleware (history)](#apidoc.element.react-router-redux.routerMiddleware)
1.  [function <span class="apidocSignatureSpan">react-router-redux.</span>routerReducer ()](#apidoc.element.react-router-redux.routerReducer)
1.  [function <span class="apidocSignatureSpan">react-router-redux.</span>syncHistoryWithStore (history, store)](#apidoc.element.react-router-redux.syncHistoryWithStore)
1.  object <span class="apidocSignatureSpan">react-router-redux.</span>actions
1.  object <span class="apidocSignatureSpan">react-router-redux.</span>middleware
1.  object <span class="apidocSignatureSpan">react-router-redux.</span>reducer
1.  object <span class="apidocSignatureSpan">react-router-redux.</span>routerActions
1.  object <span class="apidocSignatureSpan">react-router-redux.</span>sync
1.  string <span class="apidocSignatureSpan">react-router-redux.</span>CALL_HISTORY_METHOD
1.  string <span class="apidocSignatureSpan">react-router-redux.</span>LOCATION_CHANGE

#### [module react-router-redux.actions](#apidoc.module.react-router-redux.actions)
1.  [function <span class="apidocSignatureSpan">react-router-redux.actions.</span>go ()](#apidoc.element.react-router-redux.actions.go)
1.  [function <span class="apidocSignatureSpan">react-router-redux.actions.</span>goBack ()](#apidoc.element.react-router-redux.actions.goBack)
1.  [function <span class="apidocSignatureSpan">react-router-redux.actions.</span>goForward ()](#apidoc.element.react-router-redux.actions.goForward)
1.  [function <span class="apidocSignatureSpan">react-router-redux.actions.</span>push ()](#apidoc.element.react-router-redux.actions.push)
1.  [function <span class="apidocSignatureSpan">react-router-redux.actions.</span>replace ()](#apidoc.element.react-router-redux.actions.replace)
1.  object <span class="apidocSignatureSpan">react-router-redux.actions.</span>routerActions
1.  string <span class="apidocSignatureSpan">react-router-redux.actions.</span>CALL_HISTORY_METHOD

#### [module react-router-redux.middleware](#apidoc.module.react-router-redux.middleware)
1.  [function <span class="apidocSignatureSpan">react-router-redux.middleware.</span>default (history)](#apidoc.element.react-router-redux.middleware.default)

#### [module react-router-redux.reducer](#apidoc.module.react-router-redux.reducer)
1.  [function <span class="apidocSignatureSpan">react-router-redux.reducer.</span>routerReducer ()](#apidoc.element.react-router-redux.reducer.routerReducer)
1.  string <span class="apidocSignatureSpan">react-router-redux.reducer.</span>LOCATION_CHANGE

#### [module react-router-redux.routerActions](#apidoc.module.react-router-redux.routerActions)
1.  [function <span class="apidocSignatureSpan">react-router-redux.routerActions.</span>go ()](#apidoc.element.react-router-redux.routerActions.go)
1.  [function <span class="apidocSignatureSpan">react-router-redux.routerActions.</span>goBack ()](#apidoc.element.react-router-redux.routerActions.goBack)
1.  [function <span class="apidocSignatureSpan">react-router-redux.routerActions.</span>goForward ()](#apidoc.element.react-router-redux.routerActions.goForward)
1.  [function <span class="apidocSignatureSpan">react-router-redux.routerActions.</span>push ()](#apidoc.element.react-router-redux.routerActions.push)
1.  [function <span class="apidocSignatureSpan">react-router-redux.routerActions.</span>replace ()](#apidoc.element.react-router-redux.routerActions.replace)

#### [module react-router-redux.sync](#apidoc.module.react-router-redux.sync)
1.  [function <span class="apidocSignatureSpan">react-router-redux.sync.</span>default (history, store)](#apidoc.element.react-router-redux.sync.default)



# <a name="apidoc.module.react-router-redux"></a>[module react-router-redux](#apidoc.module.react-router-redux)

#### <a name="apidoc.element.react-router-redux.go"></a>[function <span class="apidocSignatureSpan">react-router-redux.</span>go ()](#apidoc.element.react-router-redux.go)
- description and source-code
```javascript
go = function () {
  for (var _len = arguments.length, args = Array(_len), _key = 0; _key < _len; _key++) {
    args[_key] = arguments[_key];
  }

  return {
    type: CALL_HISTORY_METHOD,
    payload: { method: method, args: args }
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-router-redux.goBack"></a>[function <span class="apidocSignatureSpan">react-router-redux.</span>goBack ()](#apidoc.element.react-router-redux.goBack)
- description and source-code
```javascript
goBack = function () {
  for (var _len = arguments.length, args = Array(_len), _key = 0; _key < _len; _key++) {
    args[_key] = arguments[_key];
  }

  return {
    type: CALL_HISTORY_METHOD,
    payload: { method: method, args: args }
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-router-redux.goForward"></a>[function <span class="apidocSignatureSpan">react-router-redux.</span>goForward ()](#apidoc.element.react-router-redux.goForward)
- description and source-code
```javascript
goForward = function () {
  for (var _len = arguments.length, args = Array(_len), _key = 0; _key < _len; _key++) {
    args[_key] = arguments[_key];
  }

  return {
    type: CALL_HISTORY_METHOD,
    payload: { method: method, args: args }
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-router-redux.push"></a>[function <span class="apidocSignatureSpan">react-router-redux.</span>push ()](#apidoc.element.react-router-redux.push)
- description and source-code
```javascript
push = function () {
  for (var _len = arguments.length, args = Array(_len), _key = 0; _key < _len; _key++) {
    args[_key] = arguments[_key];
  }

  return {
    type: CALL_HISTORY_METHOD,
    payload: { method: method, args: args }
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-router-redux.replace"></a>[function <span class="apidocSignatureSpan">react-router-redux.</span>replace ()](#apidoc.element.react-router-redux.replace)
- description and source-code
```javascript
replace = function () {
  for (var _len = arguments.length, args = Array(_len), _key = 0; _key < _len; _key++) {
    args[_key] = arguments[_key];
  }

  return {
    type: CALL_HISTORY_METHOD,
    payload: { method: method, args: args }
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-router-redux.routerMiddleware"></a>[function <span class="apidocSignatureSpan">react-router-redux.</span>routerMiddleware (history)](#apidoc.element.react-router-redux.routerMiddleware)
- description and source-code
```javascript
function routerMiddleware(history) {
  return function () {
    return function (next) {
      return function (action) {
        if (action.type !== _actions.CALL_HISTORY_METHOD) {
          return next(action);
        }

        var _action$payload = action.payload,
            method = _action$payload.method,
            args = _action$payload.args;

        history[method].apply(history, _toConsumableArray(args));
      };
    };
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-router-redux.routerReducer"></a>[function <span class="apidocSignatureSpan">react-router-redux.</span>routerReducer ()](#apidoc.element.react-router-redux.routerReducer)
- description and source-code
```javascript
function routerReducer() {
  var state = arguments.length > 0 && arguments[0] !== undefined ? arguments[0] : initialState;

  var _ref = arguments.length > 1 && arguments[1] !== undefined ? arguments[1] : {},
      type = _ref.type,
      payload = _ref.payload;

  if (type === LOCATION_CHANGE) {
    return _extends({}, state, { locationBeforeTransitions: payload });
  }

  return state;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-router-redux.syncHistoryWithStore"></a>[function <span class="apidocSignatureSpan">react-router-redux.</span>syncHistoryWithStore (history, store)](#apidoc.element.react-router-redux.syncHistoryWithStore)
- description and source-code
```javascript
function syncHistoryWithStore(history, store) {
  var _ref = arguments.length > 2 && arguments[2] !== undefined ? arguments[2] : {},
      _ref$selectLocationSt = _ref.selectLocationState,
      selectLocationState = _ref$selectLocationSt === undefined ? defaultSelectLocationState : _ref$selectLocationSt,
      _ref$adjustUrlOnRepla = _ref.adjustUrlOnReplay,
      adjustUrlOnReplay = _ref$adjustUrlOnRepla === undefined ? true : _ref$adjustUrlOnRepla;

  // Ensure that the reducer is mounted on the store and functioning properly.
  if (typeof selectLocationState(store.getState()) === 'undefined') {
    throw new Error('Expected the routing state to be available either as 'state.routing' ' + 'or as the custom expression you can
 specify as 'selectLocationState' ' + 'in the 'syncHistoryWithStore()' options. ' + 'Ensure you have added the 'routerReducer' to
 your store\'s ' + 'reducers via 'combineReducers' or whatever method you use to isolate ' + 'your reducers.');
  }

  var initialLocation = void 0;
  var isTimeTraveling = void 0;
  var unsubscribeFromStore = void 0;
  var unsubscribeFromHistory = void 0;
  var currentLocation = void 0;

  // What does the store say about current location?
  var getLocationInStore = function getLocationInStore(useInitialIfEmpty) {
    var locationState = selectLocationState(store.getState());
    return locationState.locationBeforeTransitions || (useInitialIfEmpty ? initialLocation : undefined);
  };

  // Init initialLocation with potential location in store
  initialLocation = getLocationInStore();

  // If the store is replayed, update the URL in the browser to match.
  if (adjustUrlOnReplay) {
    var handleStoreChange = function handleStoreChange() {
      var locationInStore = getLocationInStore(true);
      if (currentLocation === locationInStore || initialLocation === locationInStore) {
        return;
      }

      // Update address bar to reflect store state
      isTimeTraveling = true;
      currentLocation = locationInStore;
      history.transitionTo(_extends({}, locationInStore, {
        action: 'PUSH'
      }));
      isTimeTraveling = false;
    };

    unsubscribeFromStore = store.subscribe(handleStoreChange);
    handleStoreChange();
  }

  // Whenever location changes, dispatch an action to get it in the store
  var handleLocationChange = function handleLocationChange(location) {
    // ... unless we just caused that location change
    if (isTimeTraveling) {
      return;
    }

    // Remember where we are
    currentLocation = location;

    // Are we being called for the first time?
    if (!initialLocation) {
      // Remember as a fallback in case state is reset
      initialLocation = location;

      // Respect persisted location, if any
      if (getLocationInStore()) {
        return;
      }
    }

    // Tell the store to update by dispatching an action
    store.dispatch({
      type: _reducer.LOCATION_CHANGE,
      payload: location
    });
  };
  unsubscribeFromHistory = history.listen(handleLocationChange);

  // History 3.x doesn't call listen synchronously, so fire the initial location change ourselves
  if (history.getCurrentLocation) {
    handleLocationChange(history.getCurrentLocation());
  }

  // The enhanced history uses store as source of truth
  return _extends({}, history, {
    // The listeners are subscribed to the store instead of history
    listen: function listen(listener) {
      // Copy of last location.
      var lastPublishedLocation = getLocationInStore(true);

      // Keep track of whether we unsubscribed, as Redux store
      // only applies changes in subscriptions on next dispatch
      var unsubscribed = false;
      var unsubscribeFromStore = store.subscribe(function () {
        var currentLocation = getLocationInStore(true);
        if (currentLocation === lastPublishedLocation) {
          return;
        }
        lastPublishedLocation = currentLocation;
        if (!unsubscribed) {
          listener(lastPublishedLocation);
        }
      });

      // History 2.x listeners expect a synchronous call. Make the first ...
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-router-redux.actions"></a>[module react-router-redux.actions](#apidoc.module.react-router-redux.actions)

#### <a name="apidoc.element.react-router-redux.actions.go"></a>[function <span class="apidocSignatureSpan">react-router-redux.actions.</span>go ()](#apidoc.element.react-router-redux.actions.go)
- description and source-code
```javascript
go = function () {
  for (var _len = arguments.length, args = Array(_len), _key = 0; _key < _len; _key++) {
    args[_key] = arguments[_key];
  }

  return {
    type: CALL_HISTORY_METHOD,
    payload: { method: method, args: args }
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-router-redux.actions.goBack"></a>[function <span class="apidocSignatureSpan">react-router-redux.actions.</span>goBack ()](#apidoc.element.react-router-redux.actions.goBack)
- description and source-code
```javascript
goBack = function () {
  for (var _len = arguments.length, args = Array(_len), _key = 0; _key < _len; _key++) {
    args[_key] = arguments[_key];
  }

  return {
    type: CALL_HISTORY_METHOD,
    payload: { method: method, args: args }
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-router-redux.actions.goForward"></a>[function <span class="apidocSignatureSpan">react-router-redux.actions.</span>goForward ()](#apidoc.element.react-router-redux.actions.goForward)
- description and source-code
```javascript
goForward = function () {
  for (var _len = arguments.length, args = Array(_len), _key = 0; _key < _len; _key++) {
    args[_key] = arguments[_key];
  }

  return {
    type: CALL_HISTORY_METHOD,
    payload: { method: method, args: args }
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-router-redux.actions.push"></a>[function <span class="apidocSignatureSpan">react-router-redux.actions.</span>push ()](#apidoc.element.react-router-redux.actions.push)
- description and source-code
```javascript
push = function () {
  for (var _len = arguments.length, args = Array(_len), _key = 0; _key < _len; _key++) {
    args[_key] = arguments[_key];
  }

  return {
    type: CALL_HISTORY_METHOD,
    payload: { method: method, args: args }
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-router-redux.actions.replace"></a>[function <span class="apidocSignatureSpan">react-router-redux.actions.</span>replace ()](#apidoc.element.react-router-redux.actions.replace)
- description and source-code
```javascript
replace = function () {
  for (var _len = arguments.length, args = Array(_len), _key = 0; _key < _len; _key++) {
    args[_key] = arguments[_key];
  }

  return {
    type: CALL_HISTORY_METHOD,
    payload: { method: method, args: args }
  };
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-router-redux.middleware"></a>[module react-router-redux.middleware](#apidoc.module.react-router-redux.middleware)

#### <a name="apidoc.element.react-router-redux.middleware.default"></a>[function <span class="apidocSignatureSpan">react-router-redux.middleware.</span>default (history)](#apidoc.element.react-router-redux.middleware.default)
- description and source-code
```javascript
function routerMiddleware(history) {
  return function () {
    return function (next) {
      return function (action) {
        if (action.type !== _actions.CALL_HISTORY_METHOD) {
          return next(action);
        }

        var _action$payload = action.payload,
            method = _action$payload.method,
            args = _action$payload.args;

        history[method].apply(history, _toConsumableArray(args));
      };
    };
  };
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-router-redux.reducer"></a>[module react-router-redux.reducer](#apidoc.module.react-router-redux.reducer)

#### <a name="apidoc.element.react-router-redux.reducer.routerReducer"></a>[function <span class="apidocSignatureSpan">react-router-redux.reducer.</span>routerReducer ()](#apidoc.element.react-router-redux.reducer.routerReducer)
- description and source-code
```javascript
function routerReducer() {
  var state = arguments.length > 0 && arguments[0] !== undefined ? arguments[0] : initialState;

  var _ref = arguments.length > 1 && arguments[1] !== undefined ? arguments[1] : {},
      type = _ref.type,
      payload = _ref.payload;

  if (type === LOCATION_CHANGE) {
    return _extends({}, state, { locationBeforeTransitions: payload });
  }

  return state;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-router-redux.routerActions"></a>[module react-router-redux.routerActions](#apidoc.module.react-router-redux.routerActions)

#### <a name="apidoc.element.react-router-redux.routerActions.go"></a>[function <span class="apidocSignatureSpan">react-router-redux.routerActions.</span>go ()](#apidoc.element.react-router-redux.routerActions.go)
- description and source-code
```javascript
go = function () {
  for (var _len = arguments.length, args = Array(_len), _key = 0; _key < _len; _key++) {
    args[_key] = arguments[_key];
  }

  return {
    type: CALL_HISTORY_METHOD,
    payload: { method: method, args: args }
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-router-redux.routerActions.goBack"></a>[function <span class="apidocSignatureSpan">react-router-redux.routerActions.</span>goBack ()](#apidoc.element.react-router-redux.routerActions.goBack)
- description and source-code
```javascript
goBack = function () {
  for (var _len = arguments.length, args = Array(_len), _key = 0; _key < _len; _key++) {
    args[_key] = arguments[_key];
  }

  return {
    type: CALL_HISTORY_METHOD,
    payload: { method: method, args: args }
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-router-redux.routerActions.goForward"></a>[function <span class="apidocSignatureSpan">react-router-redux.routerActions.</span>goForward ()](#apidoc.element.react-router-redux.routerActions.goForward)
- description and source-code
```javascript
goForward = function () {
  for (var _len = arguments.length, args = Array(_len), _key = 0; _key < _len; _key++) {
    args[_key] = arguments[_key];
  }

  return {
    type: CALL_HISTORY_METHOD,
    payload: { method: method, args: args }
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-router-redux.routerActions.push"></a>[function <span class="apidocSignatureSpan">react-router-redux.routerActions.</span>push ()](#apidoc.element.react-router-redux.routerActions.push)
- description and source-code
```javascript
push = function () {
  for (var _len = arguments.length, args = Array(_len), _key = 0; _key < _len; _key++) {
    args[_key] = arguments[_key];
  }

  return {
    type: CALL_HISTORY_METHOD,
    payload: { method: method, args: args }
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-router-redux.routerActions.replace"></a>[function <span class="apidocSignatureSpan">react-router-redux.routerActions.</span>replace ()](#apidoc.element.react-router-redux.routerActions.replace)
- description and source-code
```javascript
replace = function () {
  for (var _len = arguments.length, args = Array(_len), _key = 0; _key < _len; _key++) {
    args[_key] = arguments[_key];
  }

  return {
    type: CALL_HISTORY_METHOD,
    payload: { method: method, args: args }
  };
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-router-redux.sync"></a>[module react-router-redux.sync](#apidoc.module.react-router-redux.sync)

#### <a name="apidoc.element.react-router-redux.sync.default"></a>[function <span class="apidocSignatureSpan">react-router-redux.sync.</span>default (history, store)](#apidoc.element.react-router-redux.sync.default)
- description and source-code
```javascript
function syncHistoryWithStore(history, store) {
  var _ref = arguments.length > 2 && arguments[2] !== undefined ? arguments[2] : {},
      _ref$selectLocationSt = _ref.selectLocationState,
      selectLocationState = _ref$selectLocationSt === undefined ? defaultSelectLocationState : _ref$selectLocationSt,
      _ref$adjustUrlOnRepla = _ref.adjustUrlOnReplay,
      adjustUrlOnReplay = _ref$adjustUrlOnRepla === undefined ? true : _ref$adjustUrlOnRepla;

  // Ensure that the reducer is mounted on the store and functioning properly.
  if (typeof selectLocationState(store.getState()) === 'undefined') {
    throw new Error('Expected the routing state to be available either as 'state.routing' ' + 'or as the custom expression you can
 specify as 'selectLocationState' ' + 'in the 'syncHistoryWithStore()' options. ' + 'Ensure you have added the 'routerReducer' to
 your store\'s ' + 'reducers via 'combineReducers' or whatever method you use to isolate ' + 'your reducers.');
  }

  var initialLocation = void 0;
  var isTimeTraveling = void 0;
  var unsubscribeFromStore = void 0;
  var unsubscribeFromHistory = void 0;
  var currentLocation = void 0;

  // What does the store say about current location?
  var getLocationInStore = function getLocationInStore(useInitialIfEmpty) {
    var locationState = selectLocationState(store.getState());
    return locationState.locationBeforeTransitions || (useInitialIfEmpty ? initialLocation : undefined);
  };

  // Init initialLocation with potential location in store
  initialLocation = getLocationInStore();

  // If the store is replayed, update the URL in the browser to match.
  if (adjustUrlOnReplay) {
    var handleStoreChange = function handleStoreChange() {
      var locationInStore = getLocationInStore(true);
      if (currentLocation === locationInStore || initialLocation === locationInStore) {
        return;
      }

      // Update address bar to reflect store state
      isTimeTraveling = true;
      currentLocation = locationInStore;
      history.transitionTo(_extends({}, locationInStore, {
        action: 'PUSH'
      }));
      isTimeTraveling = false;
    };

    unsubscribeFromStore = store.subscribe(handleStoreChange);
    handleStoreChange();
  }

  // Whenever location changes, dispatch an action to get it in the store
  var handleLocationChange = function handleLocationChange(location) {
    // ... unless we just caused that location change
    if (isTimeTraveling) {
      return;
    }

    // Remember where we are
    currentLocation = location;

    // Are we being called for the first time?
    if (!initialLocation) {
      // Remember as a fallback in case state is reset
      initialLocation = location;

      // Respect persisted location, if any
      if (getLocationInStore()) {
        return;
      }
    }

    // Tell the store to update by dispatching an action
    store.dispatch({
      type: _reducer.LOCATION_CHANGE,
      payload: location
    });
  };
  unsubscribeFromHistory = history.listen(handleLocationChange);

  // History 3.x doesn't call listen synchronously, so fire the initial location change ourselves
  if (history.getCurrentLocation) {
    handleLocationChange(history.getCurrentLocation());
  }

  // The enhanced history uses store as source of truth
  return _extends({}, history, {
    // The listeners are subscribed to the store instead of history
    listen: function listen(listener) {
      // Copy of last location.
      var lastPublishedLocation = getLocationInStore(true);

      // Keep track of whether we unsubscribed, as Redux store
      // only applies changes in subscriptions on next dispatch
      var unsubscribed = false;
      var unsubscribeFromStore = store.subscribe(function () {
        var currentLocation = getLocationInStore(true);
        if (currentLocation === lastPublishedLocation) {
          return;
        }
        lastPublishedLocation = currentLocation;
        if (!unsubscribed) {
          listener(lastPublishedLocation);
        }
      });

      // History 2.x listeners expect a synchronous call. Make the first ...
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
