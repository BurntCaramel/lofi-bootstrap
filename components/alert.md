# Alert

## Variation

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

## show_close: `Bool`

```
false
```

## view

```html
<div class="alert alert-{{ variation }} alert-dismissible" role="alert">
{{ content }}
{{#show_close}}
  <button type="button" class="close" data-dismiss="alert" aria-label="Close">
    <span aria-hidden="true">&times;</span>
  </button>
{{/show_close}}
</alert>
```
