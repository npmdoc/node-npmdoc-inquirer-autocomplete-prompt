# npmdoc-inquirer-autocomplete-prompt

#### api documentation for  inquirer-autocomplete-prompt (v0.8.0)  [![npm package](https://img.shields.io/npm/v/npmdoc-inquirer-autocomplete-prompt.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-inquirer-autocomplete-prompt) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-inquirer-autocomplete-prompt.svg)](https://travis-ci.org/npmdoc/node-npmdoc-inquirer-autocomplete-prompt)

#### Autocomplete prompt for inquirer

[![NPM](https://nodei.co/npm/inquirer-autocomplete-prompt.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/inquirer-autocomplete-prompt)

- [https://npmdoc.github.io/node-npmdoc-inquirer-autocomplete-prompt/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-inquirer-autocomplete-prompt/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-inquirer-autocomplete-prompt/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-inquirer-autocomplete-prompt/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-inquirer-autocomplete-prompt/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-inquirer-autocomplete-prompt/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "inquirer-autocomplete-prompt",
    "description": "Autocomplete prompt for inquirer",
    "version": "0.8.0",
    "dependencies": {
        "ansi-escapes": "^1.1.0",
        "chalk": "^1.1.3",
        "figures": "^2.0.0",
        "inquirer": "3.0.5",
        "lodash": "^4.17.4",
        "util": "^0.10.3"
    },
    "scripts": {
        "lint": "jshint .",
        "checkStyle": "jscs .",
        "pretest": "npm run-script lint && npm run-script checkStyle",
        "test": "istanbul cover ./node_modules/.bin/_mocha test/spec",
        "posttest": "istanbul check-coverage --statements 85 --branches 85 --functions 85 --lines 85 && rm -rf coverage"
    },
    "publishConfig": {
        "registry": "http://registry.npmjs.org"
    },
    "author": "Martin Hansen <martin@martinhansen.no>",
    "license": "ISC",
    "devDependencies": {
        "bluebird": "^3.0.5",
        "chai": "^3.4.1",
        "fuzzy": "^0.1.3",
        "istanbul": "^0.3.8",
        "jscs": "^1.6.1",
        "jshint": "^2.5.6",
        "lodash": "^3.10.1",
        "mocha": "^2.2.1",
        "promise": "^7.0.4",
        "sinon": "^1.17.2"
    },
    "repository": {
        "type": "git",
        "url": "git@github.com:mokkabonna/inquirer-autocomplete-prompt.git"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
