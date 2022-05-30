Design tokens
========================

Originally inspired on: [figma-tokens](https://github.com/klaufel/figma-tokens).

## Usage
### Config
Add a config file on the root directory of your project with the default name `designtokens.config.json` or `design-tokens.config.json`. If you chose to call it differently, specify a different config file while executing.
You can find a template for your config file [here](template.config.json)

### Execution
Add script to your package.json with the executable bin from node_modules.
```
"scripts": {
  "design-tokens": "design-tokens"
}
```

Then execute:
* `yarn design-tokens`: If you want to sync with figma.
* `yarn design-tokens platforms`: If you want to sync and compile assets.

You can specify a different config file name using the parameter `--config-file=FILENAME`.
For example:
* `yarn design-tokens --config-file=myfile.json`

## License
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

This project is under the [MIT license](LICENSE).
