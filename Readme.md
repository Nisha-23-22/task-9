# Task 9: CSS - Laundry Services Hover Effect (Transforms)

Hover effect on the "Book a service today!" CTA button of the laundry services hero section, built with plain HTML and CSS.

## Files

- `index.html` - page structure (navbar + hero section)
- `style.css` - styling, media queries and the hover effect, linked from the HTML
- `laundry.png` - laundry illustration in the hero section
- `Readme.md` - this file

## Hover effect

```css
.book-btn {
    transition: transform 0.3s ease, background-color 0.3s ease, box-shadow 0.3s ease;
}

.book-btn:hover {
    transform: scale(1.1) rotate(-5deg);
}
```

- `scale(1.1)` - the button grows in size on hover.
- `rotate(-5deg)` - the button looks tilted on hover.
- `transition` - makes the change smooth instead of instant.

The hero section stays responsive (desktop, tablet, mobile with hamburger menu) from the previous tasks.

## How to run

Keep `index.html`, `style.css` and `laundry.png` in the same folder, open `index.html` in a browser and move the mouse over the button.
