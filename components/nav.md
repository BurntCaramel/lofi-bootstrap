# Nav

```html
{{ view }}
```

## items
- First
- Second
- Third
- Fourth

## view

```html
<ul class="nav nav-pills nav-fill">
  {{#items}}
  <li class="nav-item">
    <a class="nav-link" href="#">{{ . }}</a>
  </li>
  {{/items}}
</ul>
```
