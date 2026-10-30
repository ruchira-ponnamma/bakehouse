# Fresh Crumbs Bakehouse

Fresh Crumbs Bakehouse is a responsive, multi-page bakery website built using HTML, CSS, and JavaScript. It features product categories, an automatic image slideshow, a demo order form, and browser-based feedback functionality.

**Live Website:** https://ruchira-ponnamma.github.io/bakehouse/  
**GitHub Repository:** https://github.com/ruchira-ponnamma/bakehouse

## Technologies Used

- HTML5
- CSS3
- JavaScript
- Git and GitHub Pages

## Pages and Files

- `index.html` — home page and rotating hero carousel
- `cakes.html`, `brownies.html`, `cookies.html`, `muffins.html` — category and product pages
- `order.html` — demo order form
- `feedback.html` — feedback stored in the current browser
- `splash.html` — short intro page that redirects to Home
- `style.css` — shared layout and responsive styling
- Root-level `.jpg` files — product and banner photography
- `Images/Logo.png` — site logo

## Run Locally

Open `index.html` in a browser. The site uses static HTML, CSS, and JavaScript and has no build step or package installation.

For a local web server, open a terminal in this folder and run:

```bash
py -m http.server 8000
```

Then visit `http://localhost:8000`.

## Current Limitations

The order form is a demonstration only. It validates the entered fields but does not submit, store, or send an actual order.

Feedback is stored in `localStorage` in the current browser only. It is not sent to a server or shared with other visitors, and it will not follow a visitor to another browser or device.

## Images

Product and banner photos are stored beside the HTML files and referenced using relative paths. The logo is stored in the case-sensitive `Images/` folder.

The homepage hero uses `cake-stand-with-chocolate-cherry-cake-cupcakes-web.jpg`, a reduced-size web copy; the original full-resolution image is retained alongside it.

## Deployment

The website is hosted using GitHub Pages.

The site is static and does not require a server-side runtime. Keep the relative paths and `Images` folder capitalization unchanged when uploading.
