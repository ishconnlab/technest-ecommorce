# TechNest Landing Page

A beginner-friendly ecommerce landing page inspired by the supplied TechNest screenshot. It uses plain **HTML, CSS, and JavaScript** in separate files.

## Project files

- `index.html` — page content, navigation, product cards, promotional sections, newsletter, and footer.
- `style.css` — colors, layout, typography, responsive styles, and mobile breakpoints.
- `script.js` — mobile menu, product search, demo cart count, and newsletter confirmation.
- `README.md` — this guide.

## Run the website

1. Extract the ZIP file.
2. Open the `technest` folder.
3. Double-click `index.html` to open it in your browser.

For a smoother development workflow, open the folder in VS Code and use the **Live Server** extension. Right-click `index.html`, then choose **Open with Live Server**.

## Customize it

### Change the text
Open `index.html` and edit the headings, product names, prices, and button labels.

### Change the colors
Open `style.css`. The main colors are at the top:
- `--green` — main button green.
- `--green-dark` — button hover green.
- `--ink` — main text.
- `--light` — light backgrounds.

### Change product images
Each image uses an Unsplash image URL in `index.html`. Replace the URL inside an image's `src` attribute with another image URL. An internet connection is required to load these remote images.

### Change the product list
Copy one `<article class="product-card">...</article>` block in `index.html`, then edit its `data-name`, image, product name, price, and button.

## Included interactions

- Responsive mobile navigation menu.
- Product search filters the featured products by name.
- “Shop Now” buttons update a demo cart counter.
- Newsletter form shows a confirmation message.

## Important notes

This is a **front-end demo**, not a complete online store. It does not process payments, save cart items, send newsletter emails, or connect to a product database. Those features need a backend or ecommerce service. Product photos load from Unsplash and therefore need an internet connection.

## Suggested next steps

1. Add product detail pages.
2. Store cart items in `localStorage`.
3. Connect the newsletter form to a real email service.
4. Add a backend and secure checkout before accepting real orders.
5.Hero: https://images.unsplash.com/photo-1505740420928-5e560c06d30e?auto=format&fit=crop&w=1200&q=80
   ban : https://images.unsplash.com/photo-1496181133206-80ce9b88a853?auto=format&fit=crop&w=1200&q=80
