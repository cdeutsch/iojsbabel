### About

Simple example to demonstrate issue with registering sugar before babel if you're using IO.js

### Install io.js on OSX

```
brew install iojs
```

### Run

```
/usr/local/opt/iojs/bin/iojs index.js
```

### Error

```
/Users/cdeutschx/Xamarin/iojsbabel/node_modules/sugar/release/sugar-full.development.js:6126
        fn.call(obj, key, obj[key]);
           ^
TypeError: fn.call is not a function
    at /Users/cdeutschx/Xamarin/iojsbabel/node_modules/sugar/release/sugar-full.development.js:6126:12
    at Array.forEach (native)
    at extend.keys (/Users/cdeutschx/Xamarin/iojsbabel/node_modules/sugar/release/sugar-full.development.js:6125:12)
    at /Users/cdeutschx/Xamarin/iojsbabel/node_modules/sugar/release/sugar-full.development.js:179:25
    at Array.map (native)
    at Array.<anonymous> (/Users/cdeutschx/Xamarin/iojsbabel/node_modules/sugar/release/sugar-full.development.js:180:23)
    at /Users/cdeutschx/Xamarin/iojsbabel/node_modules/babel/node_modules/babel-core/lib/babel/traversal/scope/index.js:942:137
    at Object.<anonymous> (/Users/cdeutschx/Xamarin/iojsbabel/node_modules/babel/node_modules/babel-core/lib/babel/traversal/scope/index.js:951:3)
    at Module._compile (module.js:431:26)
    at Object.Module._extensions..js (module.js:449:10)
```
