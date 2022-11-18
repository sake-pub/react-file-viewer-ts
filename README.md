# react-file-viewer-ts


## Installation:

```bash
npm install react-file-viewer-ts --save-dev
```

or

```bash
yarn add -D react-file-viewer-ts
```

## Usage :

Add `MyCounter` to your component:

```js
import React from 'react'
import ReactDOM from 'react-dom/client'
import { MyCounter } from 'react-file-viewer-ts'

const root = ReactDOM.createRoot(document.getElementById('root'));
root.render(
  <React.StrictMode>
    <div>
      <h2>Default counter</h2>
      <MyCounter />
    </div>
    <hr />
    <div>
      <h2>Counter with predefined value</h2>
      <MyCounter value={5} />
    </div>
  </React.StrictMode>
)
```

[npm-url]: https://www.npmjs.com/package/react-file-viewer-ts
[npm-image]: https://img.shields.io/npm/v/react-file-viewer-ts
[github-license]: https://img.shields.io/github/license/sake-pub/react-file-viewer-ts
[github-license-url]: https://github.com/sake-pub/react-file-viewer-ts/blob/master/LICENSE
[github-build]: https://github.com/sake-pub/react-file-viewer-ts/actions/workflows/publish.yml/badge.svg
[github-build-url]: https://github.com/sake-pub/react-file-viewer-ts/actions/workflows/publish.yml
[npm-typescript]: https://img.shields.io/npm/types/react-file-viewer-ts