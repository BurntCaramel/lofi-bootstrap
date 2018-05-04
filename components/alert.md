# Alert

## Variation: `String`

- PRIMARY
- SECONDARY
- SUCCESS
- DANGER
- WARNING
- INFO
- LIGHT
- DARK

## content: `String`

This is an important message. Ignore me at your peril.

## variation: `Variation`

PRIMARY

## showClose: `Bool`

`false`

## view

```html
<div class="alert alert-{{ variation }} alert-dismissible" role="alert">
{{ content }}
{{#showClose}}
  <button type="button" class="close" data-dismiss="alert" aria-label="Close">
    <span aria-hidden="true">&times;</span>
  </button>
{{/showClose}}
</alert>
```
