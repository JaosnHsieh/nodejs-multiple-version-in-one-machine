# nodejs-multiple-version-in-one-machine

Just knew this npm dependency `node` makes running multiple node.js version much easier from this awesome article [科普文：服务器上如何 Node 多版本共存 #31](https://github.com/atian25/blog/issues/31).

## test

```
$ cd node8
$ npm install
$ npm start
```

```
$ cd node12
$ npm install
$ npm start
```

side note:

`yarn v1.22.10` on my macos seems not running `preinstall` script in `node8/node_modules/node/package.json` so it doesn't work with yarn.
