# Gradient Text

It doesn't seem very useful. In fact it isn't.

## Demos

```demo
basic
size
custom
```

## Props

| Name | Type | Default | Description |
| --- | --- | --- | --- |
| gradient | `string \| { from: string, to: string, deg: number \| string }` | `undefined` | Text gradient color parameters. |
| size | `number \| string` | `undefined` | Text size (when the unit is not specified, the default unit: `px`). |
| type | `'primary' \| 'info' \| 'success' \| 'warning' \| 'error'` | `'primary'` | Gradient Text type. |

## Slots

| Name    | Parameters | Description                       |
| ------- | ---------- | --------------------------------- |
| default | `()`       | The content of the gradient text. |
