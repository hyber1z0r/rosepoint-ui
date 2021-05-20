# @rosepoint-ui/babel-preset

Automatically load the css for the @rosepoint-ui design system.

## Installation

```sh
npm i --save-dev @rosepoint-ui/babel-preset
# or
yarn add -D @rosepoint-ui/babel-preset
```

## Usage

.babelrc:

```json
{
  "presets": ["@rosepoint-ui/babel-preset"]
}
```

## Example

Input:

```js
import Card from '@rosepoint-ui/card';
```

Output:

```js
import Card from '@rosepoint-ui/card';
import '@rosepoint-ui/card/dist/main.css';
```
