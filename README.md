# Akachain - High Secure Transaction samples
Sample applications for implementing [hstx-node-sdk](https://github.com/Akachain/akc-node-sdk).

This project includes __hstx-front-end__, __hstx-dapp__, __hstx-chaincode__ projects.

## Installation
Before installing, [download and install Node.js](https://nodejs.org/en/download/).

Installation is done using the
[`npm install` command](https://docs.npmjs.com/getting-started/installing-npm-packages-locally):

```bash
$ npm install @akachain/hstx-node-sdk@1.0.3
```

## Quick Start

### 1. hstx-front-end
Vuejs Application

Go to directory
```js
cd hstx-front-end
```

Install dependencies
```js
npm install
```

Run in develop mode, application will be running at port 8080
```js
npm run serve
```

Build production for deployment
```js
npm run build
```

### 2. hstx-dapp
Nodejs Appplication

Go to directory
```js
cd hstx-dapp
```

Install dependencies
```js
npm install
```

Create and config _env_ (enviroment variables)
- Create file .env in the root of this project
- Copy content of .env.example to .env file
- Config env variables as you want

Run in develop mode, application will be running at port 8080
```js
npm start
```

### 3. hstx-chaincode
Goland application

Prerequisites
> akc-admin project using @akachain/akc-node-sdk