# twig-to-phtml [![NPM version][npm-image]][npm-url] [![Build Status][travis-image]][travis-url] [![Coverage percentage][coveralls-image]][coveralls-url]

> A Twig to PHTML transpiler

## Installation

```bash
npm install twig-to-phtml --save-dev
```

## Usage

```typescript
import {Transpiler} from 'twig-to-phtml';

let transpiler = new Transpiler();

transpiler.transpile('{{foo}}'); // <?=$foo?>
```

## API

Read the [documentation](https://nightlycommit.github.io/twig-to-phtml) for more information.

## Contributing

* Fork this repository
* Code
* Implement tests using [tape](https://github.com/substack/tape)
* Issue a pull request keeping in mind that all pull requests must reference an issue in the issue queue

### Running the test suite

The test suite can be run by executing the native `test` npm script:

`npm test`

### Checking code coverage

This project adheres to a strict 100% code coverage policy. Code coverage can be checked by executing the `cover` npm script:

`npm run cover`

### Generating the documentation

The documentation can be generated by executing the `build:doc` npm script:

`npm run build:doc`

This is usually not needed as the doc will be generated on every new release.

## License

Apache-2.0 © [Eric MORAND]()

[npm-image]: https://badge.fury.io/js/twig-to-phtml.svg
[npm-url]: https://npmjs.org/package/twig-to-phtml
[travis-image]: https://travis-ci.org/NightlyCommit/twig-to-phtml.svg?branch=master
[travis-url]: https://travis-ci.org/NightlyCommit/twig-to-phtml
[coveralls-image]: https://coveralls.io/repos/github/NightlyCommit/twig-to-phtml/badge.svg
[coveralls-url]: https://coveralls.io/github/NightlyCommit/twig-to-phtml