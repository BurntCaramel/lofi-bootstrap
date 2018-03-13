# Progress

```html
{{ view }}
```

## percent: `number`
75

## variation: `text`
- primary
- secondary
- success
- danger
- warning
- info

## label: `text`
{{ percent }}%

## view

```html
<div class="progress">
  <div class="progress-bar bg-{{ variation }}" role="progressbar" style="width: {{ percent }}%" aria-valuenow="{{ percent }}" aria-valuemin="0" aria-valuemax="100">{{ label }}</div>
</div>
```
