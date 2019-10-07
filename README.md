# Fewlines Stylesheets 

Disclaimer: this package is made for our internal usage and is only open source for convenience so we might not consider _Pull Requests_ or _Issues_.

Shareable stylesheets used across Fewlines websites.

## Usage

This package relies on `postcss-custom-properties`, `postcss-color-mod-function`, and `postcss-import` to work propertly.

Just include the stylesheet you want to use like this:

```css
@import "@fewlines/stylesheets/styles/colors.css";
@import "@fewlines/stylesheets/styles/fonts.css";
```
Or you can include all our css in your project like this:
```css
@import "@fewlines/stylesheets/styles/fewlines.css";
```

## Test
There is no automated testing here, but you can serve the folder and look at the `index.html` while you're making some changes in it.

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md).
