# Redux API actions

### Table of Contents

- [Getting Started](#getting-started)
  - [Installation](#installation)
  - [Usage](#usage)

# Getting Started

## Installation

```bash
$ npm install --save redux-api-actions
```

or

```bash
$ yarn add redux-api-actions
```

## Usage

```js
import { createAction } from 'redux-api-actions';

const apiRequest = createAction('actionType', () => ({
  request: {
    url: '/users',
  },
}));
```
