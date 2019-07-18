nodejs-hello-world
==
A single file nodejs server
--

This package was created to simplify the verification of a nodejs install and port availability.

## Installation

    $ git clone https://github.com/mitchallen/nodejs-hello-world.git
  
* * *

## No other install required

Because this is a simple self-contained file, you don't even need to run npm install.


## Run using default port (3000)

Switch to the **nodejs-hello-world** folder, then:

```
npm start
```

On a different computer, try to browse to http://HOST:3000.

Substitute HOST with your servers hostname or IP address.

Press Ctrl-C to stop the server

## Run on a different port

```
PORT=3001 node hello.js
```

Browse to http://HOST:3001.
