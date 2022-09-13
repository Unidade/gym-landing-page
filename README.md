![version](https://img.shields.io/badge/version-1.0.0-blue.svg) ![license](https://img.shields.io/badge/license-MIT-blue.svg)

![Product Presentation Image](https://raw.githubusercontent.com/creativetimofficial/tailwind-starter-kit/main/images/landing.jpg)

## Table of Contents

- [Description](#description)
- [Documentation](#documentation)

# Description

This is a study project where I create a landing page for a gym company

# Documentation

To run the website simple put the main.html in a browser

## Build Process

To install the dependencies run:

    npm install

To build the distribution bundles run:

```
    npx tailwindcss -i ./src/input.css -o ./dist/main.css --minify
&&
    npx webpack --mode=production
```
