# Fashion Quest

A static, responsive landing page for an online electronics store (the page title is "Shop Hero"), built with HTML, CSS and Bootstrap 5 as a front-end layout exercise. It is a single page with no custom JavaScript; interactive parts such as the carousel and the collapsible mobile navigation come from Bootstrap's bundled JavaScript.

**Live site:** https://ratulhasan001.github.io/Fashion-Quest/

## Features

- Navigation bar with logo, search field, links and cart/support icons; collapses into a toggle menu on small screens
- Hero carousel (Bootstrap carousel with indicators and previous/next controls)
- Featured product section (iPad, AirPods Max, MacBook Air)
- "Browse by category" grid with Font Awesome icons
- Product cards with image, name, price and "Buy Now" button
- Promotional sale banner and a footer with social icons and link columns
- Responsive layout using the Bootstrap grid plus a custom media query for screens up to 480px wide

## Tech stack

- HTML5, CSS3
- [Bootstrap 5.3.2](https://getbootstrap.com/) (CSS and JS bundle via CDN)
- [Font Awesome 6.4.2](https://fontawesome.com/) icons (via CDN)

## Project structure

```
Fashion-Quest/
├── index.html   # The full page
├── style.css    # Custom styles and the small-screen media query
└── img/         # Product images, logo and banner graphics
```

## Getting started

No build step is needed. Clone the repository and open `index.html` in a browser, or serve the folder locally:

```bash
git clone https://github.com/ratulhasan001/Fashion-Quest.git
cd Fashion-Quest
python3 -m http.server 8000
# then open http://localhost:8000
```

An internet connection is required for the Bootstrap and Font Awesome CDN files.

## Limitations

- This is a front-end layout only: the search box, navigation links, cart and "Buy Now" buttons are placeholders and are not wired to any functionality.

---

Ratul Hasan · [ratulhasan.dev](https://ratulhasan.dev)
