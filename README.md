

# gitbook-plugin-todos

## Fork from [ly-tools/gitbook-plugin-todo](https://github.com/ly-tools/gitbook-plugin-todo)

[![Build Status](https://travis-ci.org/ICELI/gitbook-plugin-todos.png)](https://travis-ci.org/ICELI/gitbook-plugin-todos)
[![Dependency Status](https://david-dm.org/ICELI/gitbook-plugin-todos.svg)](https://david-dm.org/ICELI/gitbook-plugin-todos)
[![devDependency Status](https://david-dm.org/ICELI/gitbook-plugin-todos/dev-status.svg)](https://david-dm.org/ICELI/gitbook-plugin-todos#info=devDependencies)
[![NPM version](http://img.shields.io/npm/v/gitbook-plugin-todos.svg?style=flat-square)](http://npmjs.org/package/gitbook-plugin-todos)
[![node](https://img.shields.io/badge/node.js-%3E=_0.12-green.svg?style=flat-square)](http://nodejs.org/download/)
[![License](http://img.shields.io/npm/l/gitbook-plugin-todos.svg?style=flat-square)](LICENSE)
[![npm download](https://img.shields.io/npm/dm/gitbook-plugin-todos.svg?style=flat-square)](https://npmjs.org/package/gitbook-plugin-todos)

## Install

```shell
$ npm install --save gitbook-plugin-todos
```

## Usage

Add the plugin to your `book.json` like this:

```javascript
{
    "plugins": ["todos"]
}
```

then in your markdown file, you can embed readonly todo list like this:

```markdown
- [ ] write some articles
    - [ ] write some articles
    - [x] drink a cup of tea
- [x] drink a cup of tea
    - [x] write some articles
    - [x] drink a cup of tea
```
