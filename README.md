# basicxss
This is a basic xss filter for node.js and its all mvc framwork
Its too easy to use and its light weight package
Installing basicxss
## Through Command Line Or with npm 
```
$ npm install basicxss
```
To add this npm package to your local machine, type the above into your command line. You’ll notice a node_modules directory appear in your root where the package is now installed.

## Without Command Line 

Add `"basicxss": "^1.0.0",` in your package.json under the dependencies i.e
```json
"dependencies": {
    "basicxss": "^1.0.0",
    }
```

# How To Use
This is the most simple part till now :)
```javascript
const basicxss = require('basicxss');
```

Then after this call the its function i.e **basicxss(arg)** and pass the string to be filtered in the argument.

###### Example
```javascript
var x = basicxss.basicxss("hello world");
console.log(x);
```
###### Output
`hello%2520world`

## More help?

[tutorial](https://www.npmjs.com/package/basicxss/tutorial)

# License

MIT License
