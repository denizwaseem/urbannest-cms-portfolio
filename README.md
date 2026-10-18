# UrbanNest — E-commerce Storefront & Content Studio

A responsive portfolio project exploring website content management, e-commerce presentation, digital campaign updates, and web quality checks. Built as a learning project for a Web Developer Associate / Web Content Management role.

> **Important scope note:** This is a front-end prototype. The content studio stores data in the current browser using `localStorage`. It has no server, database, authentication, multi-user access, payment processing, or production publishing pipeline. It demonstrates content-editing concepts but is not a replacement for learning and using a real CMS such as WordPress.

## Features

- Responsive storefront with product cards, category filters, campaign content, journal posts, and a demo shopping bag.
- Content Studio at `admin.html` to add, edit, and delete products; update homepage campaign copy; and add or delete journal posts.
- Changes are stored in browser `localStorage` and appear on the storefront in the same browser.
- Semantic HTML, form labels, alt text, keyboard-friendly controls, reduced-motion support, and responsive layouts.
- Product and editorial content is fictional and intended for demonstration.

## Run locally

No build tools or dependencies are required.

1. Download or clone this repository.
2. Open `index.html` in a modern browser. For best results, use a simple local server such as VS Code Live Server.
3. Open `admin.html` in the **same browser** to use the Content Studio.
4. Make a change in the Content Studio, save it, and refresh the storefront to see the update.

A local server option with Python (if installed):

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000` and `http://localhost:8000/admin.html`.

## Project structure

```text
urbannest-cms-portfolio/
├── index.html    # Public storefront
├── admin.html    # Browser-based content studio demo
├── styles.css    # Responsive storefront and admin styles
├── app.js        # Product rendering, filters, and demo content management
├── README.md     # Project overview and setup
└── .gitignore
```

## Suggested test checklist

- [ ] Open the site on desktop and mobile widths.
- [ ] Filter the product catalogue by category.
- [ ] Add an item to the demo bag and confirm the count changes.
- [ ] Open Content Studio and edit a product.
- [ ] Add a product and confirm it appears on the storefront.
- [ ] Update the campaign banner and verify the storefront copy.
- [ ] Add and delete a journal post.
- [ ] Refresh the pages and verify that saved content persists in the same browser.
- [ ] Check image alt text, link destinations, form validation, and browser console errors.
- [ ] Run a performance audit and record real results before claiming any performance improvement.

## Skills demonstrated

HTML5, CSS3, responsive web design, JavaScript, DOM manipulation, form validation, localStorage, content organization, campaign content updates, basic accessibility, semantic markup, and manual quality assurance.

## Known limitations and next steps

1. Replace browser-only storage with a real CMS such as WordPress or a backend/API before describing it as a production content management system.
2. Add server-side authentication and role-based access control before exposing any admin interface publicly.
3. Add automated tests, robust content validation, and a deployment workflow.
4. If using external images, confirm licensing and retain appropriate attribution where required.
5. Add WooCommerce only if building the WordPress version; this prototype does not process orders or payments.



**UrbanNest — E-commerce Storefront & Content Studio | HTML, CSS, JavaScript**

- Built a responsive storefront with product category filters, campaign content, and editorial cards.
- Developed a browser-based content studio to create, edit, and remove product and journal entries and update campaign copy.
- Used JavaScript and localStorage to persist demo content and validate forms; tested content updates and responsive behavior across screen sizes.
- Documented CMS limitations and identified next steps for integration with a production CMS.

Do not claim WordPress, WooCommerce, production authentication, real checkout, or measured performance improvements unless you implement and test those features yourself.

## License

This project is provided for educational and portfolio use. Review licenses for all third-party images and fonts before public or commercial use.
