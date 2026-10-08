# Myntra – Product Listing Page Clone

A static front-end clone of the **Myntra** online shopping website's *Electronics* product listing page. It is built with plain **HTML5** and **CSS3**, with no build step, framework or backend. It is a front-end practice assignment focused on recreating a real e-commerce layout: a navigation bar with menus, a filter sidebar, a product grid and a multi-column footer.

> **Note:** This project is for learning purposes only. Myntra and its logos, brand names and product listings belong to their respective owners, and this project is not affiliated with or endorsed by Myntra.

## Features

- Navigation bar with logo, category links (Men, Women, Kids, Home & Living, Beauty, Studio), a search box, and Profile / Wishlist / Bag icons
- "Men" dropdown mega menu and a hover menu for **Home & Living** with sub-categories (Bed Linen & Furnishing, Flooring, Bath, Home Decor)
- **Electronics** listing header with quick links and a "Sort by" dropdown (Relevance, New Arrivals, Price, Rating, Discount)
- **Filters sidebar**: Category, Brand, Price, Color and Discount checkboxes with item counts
- Product grid of cameras (FUJIFILM) and tablets (OnePlus, Realme) showing brand, product name, price, original price, discount and "Only Few Left!" tags
- Pagination controls
- Footer with Online Shopping, Useful Links and Customer Policies columns, app download badges, social icons and the return-window banner

## Tech Stack

| Technology | Usage |
| --- | --- |
| HTML5 | Page structure |
| CSS3 | Layout, hover effects and dropdown menus (`css/index.css`) |
| Font Awesome 6.5.2 | Icons, loaded from the cdnjs CDN |

## Project Structure

```
Myntra/
├── index.html       # Main page
├── css/
│   └── index.css    # All styles
└── images/          # Logo, product photos (cameras, tablets), app badges, social icons
```

## Getting Started

### Prerequisites

A modern web browser. An internet connection is needed for the Font Awesome icons, which load from a CDN.

### Run locally

1. Clone the repository:
   ```bash
   git clone https://github.com/AmanPatil2002/Assignment.git
   ```
2. Go to the project folder:
   ```bash
   cd Assignment/Myntra
   ```
3. Open `index.html` in your browser, or use a static server, for example:
   ```bash
   npx serve .
   ```

## Customization

- **Colors, fonts and layout:** edit `css/index.css`.
- **Products and prices:** edit the product blocks in `index.html` and replace the matching images in `images/`.
- **Menus and filters:** edit the navigation, `nav-detail` and filter sections in `index.html`.

## Known Limitations

- Links are placeholders (`href=""`), so navigation, filters and pagination do not work yet.
- The search box, filter checkboxes and "Sort by" dropdown are static and do nothing when used.
- The page has no responsive styles (no media queries), so it is designed for desktop screens only.
- The "Men" mega menu only contains one sample category, and the Home & Living menu uses placeholder items (Product1, Product2, ...).
- The page `<title>` is still the default "Document", and a few labels contain typos (for example "Catrgory" and "Furnishering").

## Author

**Aman Patil** – [@AmanPatil2002](https://github.com/AmanPatil2002)

## License

This project is for learning and assignment purposes. Add a license of your choice if you plan to share or reuse your own code.
