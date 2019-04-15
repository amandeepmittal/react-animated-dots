# react-animated-dots
⚛ Three dots loader for ReactJS Applications.

[![npm](https://img.shields.io/npm/v/react-animated-dots.svg?style=flat-square)](https://www.npmjs.com/package/react-animated-dots)
[![license](https://img.shields.io/github/license/mashape/apistatus.svg?style=flat-square)]()

![](http://i.imgur.com/F974dxj.gif)

## Installation

```shell
npm install --save react-animated-dots

# OR

yarn add react-animated-dots
```

## Usage
In your `.js/jsx` file:

```javascript
import React from 'react';
import { Dot } from 'react-animated-dots';

const App = () => {
  return (
    <div>
      <h2>
      // Each <Dot> is a <span> in itself
      // You can include as much <Dot> as you want
        <Dot>.</Dot>
        <Dot>.</Dot>
        <Dot>.</Dot>
      </h2>
    </div>
  );
};

export default App;
```

## Updating this package
If there's a change made in the src directory of this package, please consider running these commands in order, before publishing a major/minor/patch version over npm registery.

```shell
# !important
$ npm run dist

$ npm publish
```


### Contributions
Contributions of any kind welcome in terms of PR(s) but please follow directory structure and code conventions for better collaboration.

---

#### License
MIT
