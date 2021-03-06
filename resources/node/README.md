# node Resources

## package.json
For your portfolio beginning with  class 11, it will benefit you greatly to utilize a custom node server to use with page.js. To begin setting this up, let's first create a `package.json` file to set up our portfolio's info for npm (Node Package Manager).
1. Within the root of your project directory (where your index.html lives):
  - type `npm init` and hit enter
  - this will walk you through the steps necessary to create your own package.json file.
  - specifically, you will enter a series of values for your package.json properties. Some fields allow you to hit enter and accept the default values which will be enclosed in parenthesis.
  - you may name your app whatever you like, but a good tip would be to start with "yourName-portfolio"
  - version can be 1.0.0
  - description can be "my 301 portfolio project"
  - main should be `server.js`
  - git repository may have a default value, but if not, you can hit enter to skip that for now.
  - keywords is not necessary and you may hit enter to skip.
  - license defaults (or should default to MIT) either will be fine here.
  - It will finally ask you if this is ok? You may hit enter if so gto answer yes.

## server.js
For the server file, you may use the same code we used in lab for our server.js file.
  - Also ensure that this file is within the root of your project directory.
  - Do not forget to install your express dependency within your project terminal directory: `npm i --save express`

### Nodemon
To mimic the benefits that live-server provided to us in restarting our server everytime a file change ocurred, we can do the same with nodemon, which adds functionality on top of running a node server.
Install it like so, anywhere in your terminal: `npm i -g nodemon`

### Docs
- https://nodejs.org/en/docs/

