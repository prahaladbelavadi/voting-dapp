# voting-dapp
My first Attempt at building a voting Dapp

Commands ran:
- Install Dependenecies

```bash
$ npm install ethereumjs-testrpc web3 --save
$ npm install ethereumjs-testrpc web3@0.20.1 --save
```
- Initiate testrpc
```bash
$ node_modules/.bin/testrpc
```
- Rest are available in [here](https://medium.com/@mvmurthy/full-stack-hello-world-voting-ethereum-dapp-tutorial-part-1-40d2d0d807c2)

_Node Scripts run asynchrously;this tutorial uses the node repl directly_

#### Here's a list of errors I came across:
- [Node gyp python incompatibility](https://github.com/nodejs/node-gyp/issues/746)
- [Web page not updating](https://medium.com/@awmpietro/great-tutorial-congrats-for-that-you-provided-a-great-service-for-the-community-81f36e239f00)
  - _The contract adress needs to be changed in index.js_

Credits:
- [Tutorial by Mahesh, Founder of Zastrin](https://medium.com/@mvmurthy/full-stack-hello-world-voting-ethereum-dapp-tutorial-part-1-40d2d0d807c2)
