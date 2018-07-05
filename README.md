# CII Element
Custom Sass for Element in CII

## Install

### Using NPM to install this package

`npm install -D git+https://github.com/sunnytranco/cii-element.git`

### Replace default css of element

```sass
// Import customize sass from CII Element
@import '~cii-element/cii-element.scss';

// Import original element theme, this theme will be overwrite by cii-element.scss
@import '~element-ui/packages/theme-chalk/src/index';
```

### Using variables from partials file
In order to use those variables in your project, you need to import each partial file that you need to your manifest file. Example:

```sass
// Import partials file to use variables of colors, spacing, layer and typography
@import '~cii-element/foundation/color';
@import '~cii-element/foundation/layer';
@import '~cii-element/foundation/spacing';
@import '~cii-element/foundation/typography';
```

Note: There is no need to type underscore "_" before the name of patials file when you wanna import it to your project.

## Update
Whenever an update available, you guys will be notified on Slack. Keep it up to date yo.