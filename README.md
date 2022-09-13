![version](https://img.shields.io/badge/version-1.0.0-blue.svg) ![license](https://img.shields.io/badge/license-MIT-blue.svg)

![Product Presentation Image](./assets/img/gym-landing-page.png)

## Table of Contents

- [Description](#description)
- [Documentation](#documentation)

# Description

This is a study project where I create a landing page for a gym company

# Documentation

To run the website simple put the main.html in a browser or see the [live demo](https://gym-landing-page123.netlify.app/) here

## Build Process

To install the dependencies run:

    npm install

To build the distribution bundles run:

```
    npx tailwindcss -i ./src/input.css -o ./dist/main.css --minify
&&
    npx webpack --mode=production
```
