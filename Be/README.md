# Be – Agency Landing Page

A static, single-page agency/portfolio website built with **HTML5** and **CSS3**. The page presents a company ("Be") with sections for services, team, gallery, blog and contact details. It is a front-end practice assignment and needs no build step or backend.

![Be preview](Be.png)

## Features

- Hero/header section with logo and top navigation
- Smooth in-page navigation to each section via anchor links
- **About Us** section with image and intro text
- **Our Team** section with member cards and social icons (Font Awesome)
- **Service** section: Web design, Web development, Print design, Online marketing
- Facts/counters strip
- **Gallery** with category filter links (Show all, Web design, E-commerce, CMS, Logo)
- **Our Blog** with dated post cards and "More" links
- **Contact** section with address, phone and email, plus footer

## Tech Stack

| Technology | Usage |
| --- | --- |
| HTML5 | Page structure |
| CSS3 | Layout and styling (`css/be.css`) |
| Font Awesome 6.5.2 | Icons, loaded from the cdnjs CDN |

## Project Structure

```
Be/
├── index.html      # Main page
├── css/
│   └── be.css      # All styles
├── img/            # Logo, section backgrounds, team, blog and gallery images
│   └── gallery/    # Gallery images (emp-1.jpg ... emp-12.jpg)
└── Be.png          # Screenshot / design preview
```

## Getting Started

### Prerequisites

Just a modern web browser. An internet connection is needed for the Font Awesome icons (loaded from a CDN).

### Run locally

1. Clone the repository:
   ```bash
   git clone https://github.com/AmanPatil2002/Assignment.git
   ```
2. Open the project folder:
   ```bash
   cd Assignment/Be
   ```
3. Open `index.html` in your browser, or serve it with any static server, for example:
   ```bash
   npx serve .
   ```

## Customization

- **Colors, fonts and spacing:** edit `css/be.css`.
- **Images:** replace files in `img/` (keep the same file names, or update the paths in `index.html`).
- **Text and contact details:** edit the matching sections in `index.html`.

## Known Limitations

- Links such as "Click here", "More", the gallery filters and the social icons are placeholders and do not point anywhere yet.
- The gallery filter is static markup only, with no JavaScript filtering.
- The page `<title>` is still the default "Document".

## Author

**Aman Patil** – [@AmanPatil2002](https://github.com/AmanPatil2002)

## License

This project is for learning and assignment purposes. Add a license of your choice if you plan to share or reuse it.
