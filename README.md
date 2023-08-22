# Select2 - Bootstrap 4 theme

[![GitHub tag (with filter)](https://img.shields.io/github/v/tag/apih/select2-bootstrap4?style=flat-square)](https://github.com/apih/select2-bootstrap4)
[![jsDelivr hits (GitHub)](https://img.shields.io/jsdelivr/gh/hm/apih/select2-bootstrap4?style=flat-square)](https://www.jsdelivr.com/package/gh/apih/select2-bootstrap4)
[![GitHub](https://img.shields.io/github/license/apih/select2-bootstrap4?style=flat-square)](LICENSE.md)

A Bootstrap 4 theme for Select2. It is tailored for usage with the default Bootstrap 4. If you want to use it with custom Bootstrap 4 theme, you will need to override certain classes.

## Requirements

- Select2 4.0.13
- Bootstrap 4

## Installation

Get the file from [jsDelivr CDN](https://www.jsdelivr.com/package/gh/apih/select2-bootstrap4) and include it in your HTML page. Set the `theme` option to `bootstrap4` when initializing the component.

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/apih/select2-bootstrap4@latest/dist/style.min.css">

<script>
    $('#element').select2({
        theme: 'bootstrap4',
    });
</script>
```
