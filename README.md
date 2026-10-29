# Fresh Crumbs Bakehouse

Fresh Crumbs Bakehouse is a small static bakery website for browsing cakes, brownies, cookies, and muffins, with demo order and browser-local feedback pages.

## Pages and files

- `index.html` — home page and rotating hero carousel
- `cakes.html`, `brownies.html`, `cookies.html`, `muffins.html` — category and product pages
- `order.html` — demo order form
- `feedback.html` — feedback stored in the current browser
- `splash.html` — short intro page that redirects to Home
- `style.css` — shared layout and responsive styling
- Root-level `.jpg` files — product and banner photography
- `Images/Logo.png` — site logo

## Run locally

Open `index.html` in a browser. The site uses static HTML, CSS, and JavaScript and has no build step or package installation. For a local web server, open a terminal in this folder and run `py -m http.server 8000`, then visit `http://localhost:8000`.

## Current limitations

The order form is a demonstration only. It validates the entered fields but does not submit, store, or send an order. To place an order, contact the bakery by phone.

Feedback is stored in `localStorage` in the current browser only. It is not sent to or shared with the bakery or other visitors, and it will not follow a visitor to another browser or device.

## Images

Product and banner photos are stored beside the HTML files and referenced using relative paths. The logo is stored in the case-sensitive `Images/` folder. The homepage hero uses `cake-stand-with-chocolate-cherry-cake-cupcakes-web.jpg`, a reduced-size web copy; the original full-resolution image is retained alongside it.

## Deploy to GitHub Pages

1. Create a GitHub repository and add the contents of this folder.
2. In the repository, open **Settings → Pages**.
3. Choose **Deploy from a branch**, select the branch containing the site and the repository root folder, then save.
4. Wait for GitHub Pages to finish publishing and open the URL shown in the Pages settings.

The site is static and does not require a server-side runtime. Keep the relative paths and `Images` folder capitalization unchanged when uploading.
