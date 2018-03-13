# Breadcrumb

## current
- DVDs

## parents
- Home
- Library

## view

```html
<nav aria-label="breadcrumb">
  <ol class="breadcrumb">
    {{#parents}}
    <li class="breadcrumb-item"><a href="#">{{ . }}</a></li>
    {{/parents}}
    <li class="breadcrumb-item active" aria-current="page">{{ current }}</li>
  </ol>
</nav>
```
