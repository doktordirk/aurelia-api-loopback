# Aurelia-api-loopback-sample

This is an enhanced sample based on paul van bladel's [aurelia-loopback-sample](https://github.com/paulvanbladel/aurelia-loopback-sample/).

This version uses aurelia-api for rest api access.

## Installation instructions
```
git clone https://github.com/dirkeisinger/aurelia-api-loopback-sample
cd aurelia-api-loopback-sample
npm install
cd client
npm install
jspm install
```

##how to run the sample
You need to open two command prompts. One in the client folder and one in the server folder.
In the server folder type:
```
node server.js
```
This should give following output:
```
λ node server.js
Browse your REST API at http://localhost:3000/explorer
Web server listening at: http://localhost:3000/
```
In the client folder type:
```
gulp watch
```
