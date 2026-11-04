# Laundry Services – Responsive Hero Section

A responsive version of the laundry web app hero section, built with plain HTML and CSS (no Bootstrap).

## Files

- `index.html` – page markup
- `style.css` – all styling and media queries
- `Readme.md` – this file
- `images/washing-machine.png` – hero image (add your own image here)

## What was done

**Navbar**

- Uses `display: flex` (instead of `inline`) for the navbar and the link list.
- Tablet (≤ 992px): smaller logo, link and username text.
- Mobile (≤ 600px): links are hidden; only the logo and username are shown.

**Hero Section**

- Desktop: text on the left, image on the right (flex row).
- Tablet (≤ 992px): reduced heading, paragraph, button and image sizes.
- Mobile (≤ 600px): `flex-direction: column` – text and button on top, image below.

## Breakpoints

| Device  | Width   |
| ------- | ------- |
| Desktop | > 992px |
| Tablet  | ≤ 992px |
| Mobile  | ≤ 600px |

## How to run

1. Put the washing machine image in an `images` folder as `washing-machine.png`.
2. Open `index.html` in a browser (or use Live Server).
3. Use Chrome DevTools device toolbar (iPad Mini 768px, 375px mobile) to test.
