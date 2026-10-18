# UrbanNest — E-commerce Storefront & Content Studio

UrbanNest is a small e-commerce website built with HTML, CSS, and JavaScript. It has a product catalogue, category filters, promotional content, journal posts, and a simple content editor.

**Live Demo:** https://denizwaseem.github.io/urbannest-cms-portfolio/  
**GitHub:** https://github.com/denizwaseem/urbannest-cms-portfolio

## Features

- Browse products and filter them by category.
- View promotional content and journal posts.
- Use the demo shopping bag to add items.
- Open `admin.html` to add, edit, or delete products and journal posts.
- Update the homepage campaign text from the Content Studio.
- Save changes in the browser using `localStorage`.
- Responsive layout for different screen sizes.

## Built With

- HTML5
- CSS3
- JavaScript
- Browser `localStorage`
- GitHub Pages

## Run Locally

You can run the project without installing any packages.

1. Download or clone the repository.
2. Open the project folder.
3. Open `index.html` in your browser.
4. Open `admin.html` in the same browser to use the Content Studio.

For a local server, you can use VS Code Live Server or run this command if Python is installed:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000` for the storefront or `http://localhost:8000/admin.html` for the Content Studio.

## Project Structure

```text
urbannest-cms-portfolio/
├── index.html
├── admin.html
├── styles.css
├── app.js
├── README.md
├── .gitignore
└── LICENSE
```

- `index.html` — storefront
- `admin.html` — content editor
- `styles.css` — styling for both pages
- `app.js` — product display, filtering, and content editing
- `README.md` — project documentation

## Testing

Things to check when running the project:

- Product category filters work correctly.
- Items can be added to the demo shopping bag.
- Products can be added, edited, and deleted in the Content Studio.
- Campaign text and journal posts can be updated.
- Changes remain after refreshing the pages in the same browser.
- The layout works on mobile and desktop screens.
- Links, images, and forms work as expected.

## Limitations

This is a front-end demo, not a production e-commerce site or a full CMS.

- Content is saved in the current browser using `localStorage`.
- Changes are not shared between different browsers or devices.
- There is no backend, database, or user authentication.
- The shopping bag does not process real orders or payments.
- The Content Studio is for demonstration purposes and is not secure for managing real customer or business data.

## Future Improvements

- Build a WordPress version to practise using a real CMS.
- Add WooCommerce for product and store management.
- Improve error handling and add automated tests.
- Test accessibility and measure website performance.

## License

See the `LICENSE` file for the terms that apply to this project. Check the licenses of any third-party images or fonts used.
