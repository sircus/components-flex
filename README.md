# sircus-components-flex

[![npm version](https://img.shields.io/npm/v/sircus-components-flex.svg?style=flat)](https://www.npmjs.com/package/sircus-components-flex)


## Installation

> npm:

```bash
$ npm install sircus-components-flex sircus-tools-width sircus-tools-gutter
```

## Usage

> cssnext:

input.css
```css
@import "sircus-components-flex";
@import "sircus-tools-width";
@import "sircus-tools-gutter";
```

> sass:

input.scss
```scss
@import "./node_modules/sircus-components-flex/converted";
@import "./node_modules/sircus-tools-width/converted";
@import "./node_modules/sircus-tools-gutter/converted";
```


> Markup

```html
<div class="Flex t-gutter">
  <div class="Flex-col t-width1of4">
    1
  </div>
  <div class="Flex-col t-width1of4">
    2
  </div>
  <div class="Flex-col t-width1of4">
    3
  </div>
  <div class="Flex-col t-width1of4">
    4
  </div>
</div>
```

> Modifier

```css
.Flex--nowrap       { flex-wrap: nowrap; }
.Flex--center       { justify-content: center; }
.Flex--right        { justify-content: flex-end; }
.Flex--left         { justify-content: flex-start; }
.Flex--justify      { justify-content: space-between; }
.Flex--top          { align-items: flex-start; }
.Flex--middle       { align-items: center; }
.Flex--bottom       { align-items: flex-end; }
.Flex--baseline     { align-items: baseline; }
/* child */
.Flex-col--fit      { flex: 1; }
.Flex-col--first    { order: -1 }
.Flex-col--last     { order: 9999 }
```


## Contributing

We Need Your Help!


## License
Released under the [MIT](https://github.com/sircus/license/blob/master/LICENSE) license.
