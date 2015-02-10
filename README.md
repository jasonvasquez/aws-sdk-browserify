# aws-sdk + browserify

This is a demonstration app for the issues I'm having using aws-sdk with browserify.

### How to test

1. Clone the repository
2. `npm install`
3. `npm run build` _or_ `browserify index.js > bundle.js`

### My results

    $ NODE_ENV=production browserify . > bundle.js
    Error: ENOTDIR, stat '<....>/aws-sdk-browserify/node_modules/aws-sdk/lib/browser.js/dist-tools/transform.js'
    at Error (native)

### My platform

* OS: MacOS 10.10.2
* Node: v0.12.0
* aws-sdk: 2.1.8
* browserify: 8.1.3