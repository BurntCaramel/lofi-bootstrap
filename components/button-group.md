# Button Group

## items
- Left
- Middle
- Right

## variation: `text`
- primary
- secondary
- success
- danger
- warning
- info

## view

```html
<div class="btn-group" role="group" aria-label="Basic example">
  {{#items}}
  <button type="button" class="btn btn-{{ variation }}">{{ . }}</button>
  {{/items}}
</div>
```
