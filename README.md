# null_or_empty

[![Node CI](https://github.com/kalwar/null_or_empty/actions/workflows/whatever.yml/badge.svg)](https://github.com/kalwar/null_or_empty/actions/workflows/whatever.yml)
[![Node CI](https://github.com/maria-aluko/CI-CD/actions/workflows/whatever.yml/badge.svg?event=push)](https://github.com/maria-aluko/CI-CD/actions/workflows/whatever.yml)
![Buildbot Status](https://img.shields.io/badge/Buildbot-Working%20Hard%20%F0%9F%92%BB-green)

A simple Node.js package that checks, if a given string is null or empty.

## Usage

First, install the package using npm:

    npm install @skalwar/null_or_empty --save

Then, require the package and use it like so:

    var isNullOrEmpty = require('@skalwar/null_or_empty');

    console.log(isNullOrEmpty("")); // true
    console.log(isNullOrEmpty(null)); // true
    console.log(isNullOrEmpty(undefined)); // true

    console.log(isNullOrEmpty("Hello World")); // false

## License

MIT
