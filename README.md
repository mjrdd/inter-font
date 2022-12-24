# @mjrdd/inter

CSS and web font files for self-hosting Inter fonts.

Visit the source: [Inter](https://rsms.me/inter/).

Font version: 3.19

## Installation

```bash
npm install --save @mjrdd/inter
```

## Setup

```js
import "@mjrdd/inter";
```

Then, reference the font in a CSS stylesheet:

```css
:root {
  font-family: "Inter", sans-serif;
}

@supports (font-variation-settings: normal) {
  :root {
    font-family: "Inter var", sans-serif;
  }
}
```
