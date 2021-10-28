# Stock API libjs
[![Open In Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.dev.cloud.adobestock.com/#https://github.com/MasonM/stock-api-libjs)

## Overview
This is a Javascript implementation of the various APIs provided by the Stock services.

## Before You Begin
Get a Stock API Key by [creating a Creative Cloud Adobe Stock integration on console.adobe.io](https://console.adobe.io/integrations/new).

### Requirements

- [node.js](https://nodejs.org) v6.3.1 or newer
- [`yarn`](https://yarnpkg.com/en/docs/install)

### Install Dependencies
- `yarn install`

## Build
- `yarn run build`

Creates the JavaScript library file under the `dist/` directory.

## Usage
Check out the [usage documentation](USAGE.md)!

## Running the Test Suite
- `yarn test` ( eslint, mocha )
This also generates code coverage report using karma test runner.

### Linting
- `yarn run lint`
