# react-animated-dots
⚛ Three dots loader for Reactjs Applications.

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
