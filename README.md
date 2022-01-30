# @curios/tailwind-balloons

This tailwind plugin let's you to add `data-balloon-(up | down | left | right)` attributes on any valid dom element. This will show a tooltip, on hover on the that element with the text added to the data-balloon-\* attribute.

## For example

```jsx
<button
  className="px-4 py-2 border rounded bg-white"
  data-balloon-down="Copy to clipboard"
  type="button"
>
  Copy
</button>
```

This will show the text _"Copy to clipboard"_ below the button on hovering over it.
