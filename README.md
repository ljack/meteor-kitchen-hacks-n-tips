# meteor-kitchen-hacks
meteor-kitchen hacks and snippets 

## Table of Contents
1. [Display helpers](#helpers)
1. [Template](#template)
1. [Template](#template)


## Helpers
- [1.1](#1.1) <a name='1.1'></a> **Custom HTML output**: When you want to generate custom HTML for a field.
```javascript
Template.registerHelper("displayPhoto",  function (url) {
  let html = `<img src="${url}" />`;
  return Spacebars.SafeString(html);
} );
```

## Template
