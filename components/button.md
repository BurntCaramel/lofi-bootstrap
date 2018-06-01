# Button

A button with several `variation`s.

## variation: String
- primary
- secondary
- success
- danger
- warning
- info

## class: String

## content: [Element]
Click me

## view
```html
<button class="btn btn-{{ variation }} {{ class }}">{{ content }}</button>
```
