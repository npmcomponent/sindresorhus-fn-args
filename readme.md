*This repository is a mirror of the [component](http://component.io) module [sindresorhus/fn-args](http://github.com/sindresorhus/fn-args). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/sindresorhus-fn-args`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*
# fn-args [![Build Status](https://travis-ci.org/sindresorhus/fn-args.svg?branch=master)](https://travis-ci.org/sindresorhus/fn-args)

> Get the arguments of a function


## Install

Download [manually](https://github.com/sindresorhus/fn-args/releases) or with a package-manager.

```bash
$ npm install --save fn-args
```

```bash
$ bower install --save fn-args
```

```bash
$ component install sindresorhus/fn-args
```


## Usage

```js
var fn = function (foo, bar) {};

fnArgs(fn);
//=> ['foo', 'bar']
```


## License

[MIT](http://opensource.org/licenses/MIT) © [Sindre Sorhus](http://sindresorhus.com)
