# Alert

## content: `elements`
This is an important message. Ignore me at your peril.

## variation: `text`
- primary
- secondary
- success
- danger
- warning
- info
- light
- dark

## show_close: `bool`
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
