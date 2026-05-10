# SCSS WebFont Lato

Package for integrating `Lato` fonts in a web environment.

![npm](https://img.shields.io/npm/v/@bu0nq/scss-webfont-lato?style=for-the-badge)
![npm](https://img.shields.io/npm/dm/@bu0nq/scss-webfont-lato?style=for-the-badge)
![npm](https://img.shields.io/npm/dt/@bu0nq/scss-webfont-lato?style=for-the-badge)
___

## Installation

This package can be deployed automatically using NPM:

```
npm i @bu0nq/scss-webfont-lato
```

## Usage (SCSS)

Font files are located in the `fonts` directory. To import all fonts, you can use:

```scss
body {
  font-family: 'Lato', sans-serif;
}
```

### Importing

```scss
@use "@bu0nq/scss-webfont-lato";
```

To import specific fonts, you can use:

```scss
@use "@bu0nq/scss-webfont-lato/lato-100-italic";
@use "@bu0nq/scss-webfont-lato/lato-100-normal";
@use "@bu0nq/scss-webfont-lato/lato-200-italic";
@use "@bu0nq/scss-webfont-lato/lato-200-normal";
@use "@bu0nq/scss-webfont-lato/lato-300-italic";
@use "@bu0nq/scss-webfont-latolato-300-normal";
@use "@bu0nq/scss-webfont-lato/lato-400-italic";
@use "@bu0nq/scss-webfont-lato/lato-400-normal";
@use "@bu0nq/scss-webfont-lato/lato-500-italic";
@use "@bu0nq/scss-webfont-lato/lato-500-normal";
@use "@bu0nq/scss-webfont-lato/lato-600-italic";
@use "@bu0nq/scss-webfont-lato/lato-600-normal";
@use "@bu0nq/scss-webfont-lato/lato-700-italic";
@use "@bu0nq/scss-webfont-lato/lato-700-normal";
@use "@bu0nq/scss-webfont-lato/lato-800-italic";
@use "@bu0nq/scss-webfont-lato/lato-800-normal";
@use "@bu0nq/scss-webfont-lato/lato-900-italic";
@use "@bu0nq/scss-webfont-lato/lato-900-normal";
```

## Licensing

It is important to always read the license for every font that you use. Most of the fonts in the collection use the `SIL
Open Font License v1.1`. Some fonts use the `Apache 2.0` license. The Ubuntu fonts use the `Ubuntu Font License v1.0`.
