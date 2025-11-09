# scrollable-cards

Web Components for Horizontal Scrolling Cards.



<video aria-label="several colored cards horizontally spread out. As they are scrolled they stick to the left side of the window." src="https://github.com/user-attachments/assets/ac8b7705-4f4e-4cd8-9c88-39ce11a3e7ed"></video>



## How to Use

You can include the project directly in any project by including the script (either the source from this repo, or your
favorite CDN).

```html
<script src="https://unpkg.com/scrollable-cards@1"></script>
```

That will register two components you can use directly in your project:

- `<sc-container>` - a scroll container for all of the cards you want to include
- `<sc-card>` - a single card that will stick to the start of a scroll container when scrolled

As a minimal example, you could have the following:

```html
<sc-container>
  <sc-card>First Card</sc-card>
  <sc-card>Second Card</sc-card>
  <sc-card>Third Card</sc-card>
</sc-container>
```

Both the `<sc-container>` and `<sc-card>` are directly stylable, so if you want to control the height, width, color, or
any other attribute, you can simple write CSS pointing to `sc-container` or `sc-card`.

## Live Examples

You can pull this repo down, or take a look at the following code-pens to see live examples:

- Colorful Cards - https://codepen.io/JRJurman/pen/VYeJEYj
- Notes - https://codepen.io/JRJurman/pen/QwyXZwx
- Baked Pasta Recipe - https://codepen.io/JRJurman/pen/emJwPmX

## Inspiration

Inspired by the design affordances of Innos Notes (no longer available).

## Development

This uses [Inline HTML](https://marketplace.visualstudio.com/items?itemName=pushqrdx.inline-html) for intellisense of
inline HTML and CSS.
