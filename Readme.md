# babel-plugin-json-to-proptypes

> Convert JSON to React PropTypes

Online REPL is available at https://transform.now.sh/

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

## Contributors

Thanks goes to these wonderful people ([emoji key](https://github.com/kentcdodds/all-contributors#emoji-key)):

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
| [<img src="https://avatars3.githubusercontent.com/u/5389035?v=4" width="100px;"/><br /><sub>Ritesh Kumar</sub>](http://riteshkr.com)<br />[📖](https://github.com//babel-plugin-json-to-proptypes/commits?author=ritz078 "Documentation") [💻](https://github.com//babel-plugin-json-to-proptypes/commits?author=ritz078 "Code") [🤔](#ideas-ritz078 "Ideas, Planning, & Feedback") |
| :---: |
<!-- ALL-CONTRIBUTORS-LIST:END -->

This project follows the [all-contributors](https://github.com/kentcdodds/all-contributors) specification. Contributions of any kind welcome!