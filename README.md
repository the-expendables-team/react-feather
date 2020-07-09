## React Feather Icons

[![npm version](https://img.shields.io/npm/v/react-feather.svg?style=flat-square)](https://www.npmjs.com/package/react-feather)
[![npm downloads](https://img.shields.io/npm/dm/react-feather.svg?style=flat-square)](https://www.npmjs.com/package/react-feather)

#### What is react-feather?
react-feather is a collection of simply beautiful open source icons for React.js. Each icon is designed on a 24x24 grid with an emphasis on simplicity, consistency and readability.

#### Based on Feather Icons  ```v4.28.0```

### Installation
    yarn add react-feather
    
  or
    
    npm i react-feather

### Usage

```javascript
import React from 'react';
import { Camera } from 'react-feather';

const App = () => {
  return <Camera />
};

export default App;
```

Icons can be configured with inline props:
```javascript
<Camera color="red" size={48} />
```

If you can't use ES6 imports, it's possible to include icons from the compiled folder ./dist.
```javascript
var Camera = require('react-feather/dist/icons/camera').default;

var MyComponent = React.createClass({
  render: function () {
    return (
      <Camera />
    );
  }
});
```
You can also include the whole icon pack:

```javascript
import React from 'react';
import * as Icon from 'react-feather';

const App = () => {
  return <Icon.Camera />
};

export default App;
```

<div style="display: flex; justify-content: center;">
    <div style="display: flex; justify-content: center; align-items: center; border: 1px solid #ddd; min-width: 80px; height: 80px; margin: 6px; flex-direction: column;">
        
        <svg style="margin-bottom: 8px;" xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="feather feather-activity"><polyline points="22 12 18 12 15 21 9 3 6 12 2 12"></polyline></svg>
        <div><pre>&lt;Activity/&gt;</pre></div>
    </div>;
    <div style="display: flex; justify-content: center; align-items: center; border: 1px solid #ddd; width: 80px; height: 80px; margin: 6px;">
        Other
    </div>
<div>
