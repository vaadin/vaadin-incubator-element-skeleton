[![Build Status](https://travis-ci.org/vaadin/vaadin-incubator-element.svg?branch=master)](https://travis-ci.org/vaadin/vaadin-incubator-element)
[![Gitter](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/vaadin/web-components?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge)

# &lt;vaadin-incubator-element&gt;

[Live Demo ↗](https://vaadin.com/components/vaadin-incubator-element/html-examples)
|
[API documentation ↗](https://vaadin.com/components/vaadin-incubator-element/html-api)


[&lt;vaadin-incubator-element&gt;](https://vaadin.com/components/vaadin-incubator-element) is a Web Component providing an easy way to ask the user to confirm a choice, part of the [Vaadin components](https://vaadin.com/components).

```html
  <vaadin-incubator-element header="Unsaved changes" confirm-text="Save" on-confirm="save"
    cancel on-cancel="cancel" reject reject-text="Discard" on-reject="discard">
    Do you want to save or discard your changes before navigating away?
  </vaadin-incubator-element>
```

[<img src="https://raw.githubusercontent.com/vaadin/vaadin-incubator-element/master/screenshot.png" width="200" alt="Screenshot of vaadin-incubator-element">](https://vaadin.com/components/vaadin-incubator-element)


## Installation

The Vaadin components are distributed as Bower and npm packages.
Please note that the version range is the same, as the API has not changed.
You should not mix Bower and npm versions in the same application, though.

Unlike the official Polymer Elements, the converted Polymer 3 compatible Vaadin components
are only published on npm, not pushed to GitHub repositories.

### Polymer 2 and HTML Imports compatible version

Install `vaadin-incubator-element`:

```sh
bower i vaadin/vaadin-incubator-element --save
```

Once installed, import it in your application:

```html
<link rel="import" href="bower_components/vaadin-incubator-element/vaadin-incubator-element.html">
```
### Polymer 3 and ES Modules compatible version


Install `vaadin-incubator-element`:

```sh
npm i @vaadin/vaadin-incubator-element --save
```

Once installed, import it in your application:

```js
import '@vaadin/vaadin-incubator-element/vaadin-incubator-element.js';
```

## Getting Started

Vaadin components use the Lumo theme by default.

## The file structure for Vaadin components

- `src/vaadin-incubator-element.html`

  Unstyled component.

- `theme/lumo/vaadin-incubator-element.html`

  Component with Lumo theme.

- `vaadin-incubator-element.html`

  Alias for theme/lumo/vaadin-incubator-element.html


## Running demos and tests in browser

1. Fork the `vaadin-incubator-element` repository and clone it locally.

1. Make sure you have [npm](https://www.npmjs.com/) installed.

1. When in the `vaadin-incubator-element` directory, run `npm install` and then `bower install` to install dependencies.

1. Run `polymer serve --open`, browser will automatically open the component API documentation.

1. You can also open demo or in-browser tests by adding **demo** or **test** to the URL, for example:

  - http://127.0.0.1:8080/components/vaadin-incubator-element/demo
  - http://127.0.0.1:8080/components/vaadin-incubator-element/test


## Running tests from the command line

1. When in the `vaadin-incubator-element` directory, run `polymer test`


## Following the coding style

We are using [ESLint](http://eslint.org/) for linting JavaScript code. You can check if your code is following our standards by running `gulp lint`, which will automatically lint all `.js` files as well as JavaScript snippets inside `.html` files.


## Contributing

  - Make sure your code is compliant with our code linters: `gulp lint`
  - Check that tests are passing: `polymer test`
  - [Submit a pull request](https://www.digitalocean.com/community/tutorials/how-to-create-a-pull-request-on-github) with detailed title and description
  - Wait for response from one of Vaadin components team members


## License

Commercial Vaadin Add-on License version 3 (CVALv3). For license terms, see LICENSE.

Vaadin collects development time usage statistics to improve this product. For details and to opt-out, see https://github.com/vaadin/vaadin-usage-statistics.
