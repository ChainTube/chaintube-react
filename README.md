# ChainTube-react

This is the front-end of ChainTube. It is a HTML5 app written in React and TypeScript.

## Deploy the app
WIP - please have a few more days patience

The app runs from any web server without the need for any server-side technologies (no nodejs, no PHP, ...). You simply need to upload and unpack
the `chaintube.zip` file to your web server.

Optional custom config can be set inside the `index.html` file:
```javascript
        var tubeConf = { // optional config overrides. Remove properties to use defaults
            debug: true, // whether to print debug logs to browser console
            pathRoot: "/", // the root directory path where your app is hosted
            api: {
                bchdWeb: "https://bchd.cashtippr.com:9000", // the BCHD backend using grpc-web
                streamerWeb: "https://127.0.0.1:9005" // the streamer backend using grpc-web
            }
        }
```
