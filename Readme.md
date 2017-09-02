# babel-plugin-json-to-proptypes

> Convert JSON to React PropTypes

## Installation
```
npm i -D babel-plugin-json-to-proptypes
```

## Usage

```js
import { transform } from "babel-core"
import jsonToProptypes from "babel-plugin-json-to-proptypes"

const json = `{
  a: 'b'
}`

const { code } = transform(json, {
  plugins: [jsonToProptypes]
})

console.log(code)

// const propTypes = {
//  a: PropTypes.string  
// }
```

## License
MIT @ Ritesh Kumar


