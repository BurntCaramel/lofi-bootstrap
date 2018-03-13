# Card

```html
{{ view }}
```

## size
400

## subject: text
beach

## unsplash_url
https://source.unsplash.com/{{size * 2}}x{{size * 2}}?{{subject}}

## view
```html
<div class="card" style="width: {{ size }}px">
  <img class="card-img-top" src="{{ unsplash_url }}" alt="{{ subject }}">
  <div class="card-body">
    <h5 class="card-title">{{ subject }}</h5>
  </div>
</div>
```
