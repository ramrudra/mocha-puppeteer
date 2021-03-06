# mocha-puppeteer

Since the release of Google Chrome headless mode, the Chrome DevTools team has developed
[puppeteer](https://github.com/GoogleChrome/puppeteer) for running and managing an instance of Chromium.
This module makes it possible to run tests written with
[mocha](https://github.com/mochajs/mocha) inside of a Chromium instance.


*Note:* Still under dev. Nothing is really configurable right now. Come back later.

## Installation

```
npm i -D mocha-puppeteer
```

## Usage

To run your tests, you can pass a glob to the exposed cli tool.

```
npx mocha-puppeteer ./tests/**/*.js
```

## Contributing

If you find a bug or have an idea about how to improve the module, please create an issue. If you have a fix
for a bug, feel free to submit a pull request.

You can run tests with the `npm test` command.
