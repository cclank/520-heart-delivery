# 520 Heart Delivery

[![Demo](https://img.shields.io/website?url=https%3A%2F%2F520-heart-delivery.pages.dev%2F&label=demo&up_message=online&down_message=offline)](https://520-heart-delivery.pages.dev/)
[![Cloudflare Pages](https://img.shields.io/badge/Cloudflare%20Pages-deployed-F38020?logo=cloudflarepages&logoColor=white)](https://520-heart-delivery.pages.dev/)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)](index.html)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)](index.html)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=111)](index.html)

A single-file romantic interactive landing page for 520 gifting moments, with animated heart delivery, personalized name tags, selectable heart themes, and a lightweight static deployment footprint.

Live demo: [520-heart-delivery.pages.dev](https://520-heart-delivery.pages.dev/)

## Features

- Animated heart delivery along a hand-drawn Bezier path
- Personalized sender and receiver names through a modal form
- Multiple heart styles: red, pink, sparkle, and gold
- Scroll, touch, dropdown, and click interactions
- Hand-drawn SVG characters and paper-texture visual treatment
- Fully static HTML/CSS/JavaScript, no build step required
- Cloudflare Pages-ready deployment

## Preview

Open the live demo and use any of these interactions:

- Scroll down to send hearts continuously
- Click the central heart or bottom arrow to send one heart
- Pick a heart theme from the dropdown for a short burst
- Click `专属定制` to customize the two name tags

## Project Structure

```text
.
├── index.html
├── LICENSE
└── README.md
```

## Local Development

Any static file server works:

```bash
python3 -m http.server 8789
```

Then open:

```text
http://127.0.0.1:8789/
```

You can also open `index.html` directly in a browser.

## Deploy

The project is already deployed on Cloudflare Pages. To redeploy manually:

```bash
npx wrangler pages deploy . --project-name=520-heart-delivery --branch=main
```

## Customization

- Update copy, colors, and layout in `index.html`
- Replace the logo text if you are using this outside a private demo
- Adjust animation speed in `createHeart()`
- Edit the theme palette in `heartThemes`

## Trademark Note

The sample page includes brand-like placeholder text in the header. Replace it before public commercial use if you do not own the relevant brand rights.

## License

MIT License. See [LICENSE](LICENSE).
