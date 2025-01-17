---
eleventyNavigation:
  parent: Template Languages
  key: HAML
  order: 10
layout: layouts/langs.njk
---
| Eleventy Short Name | File Extension | npm Package    |
| ------------------- | -------------- | -------------- |
| `haml`              | `.haml`        | [`haml.js`](https://github.com/tj/haml.js) |

You can override a `.haml` file’s template engine. Read more at [Changing a Template’s Rendering Engine](/docs/languages/).

## HAML Options

### Optional: Set your own Library instance {% addedin "0.3.0" %}

As an escape mechanism for advanced usage, pass in your own instance of the HAML library using the Configuration API.

```js
module.exports = function(eleventyConfig) {
  let haml = require("hamljs");
  eleventyConfig.setLibrary("haml", haml);
};
```

## Supported Features

| Feature                                                                             | Syntax                                                                 |
| ----------------------------------------------------------------------------------- | ---------------------------------------------------------------------- |
| 🚫 Filters                                                                   | **Not yet supported** `:filterName some text` Read more about [Filters](/docs/filters/).                                                |
| 🚫 [Eleventy Universal Filters](/docs/filters/#universal-filters) | **Not yet supported** `:filterName some text` Read more about [Filters](/docs/filters/). |
