# Cuda – Creative Agency Landing Page

A static, single-page landing page for a fictional web and mobile app agency called **Cuda**. It is built with plain **HTML5** and **CSS3**, with no build step, framework or backend. It is a front-end practice assignment focused on layout, sections and responsive styling.

## Features

- Hero section with logo, top navigation and a "WORK WITH US" call-to-action
- **Services We Provide**: Branding, Design, Development and Rocket Science
- **Meet Our Team**: four member cards with role, short bio and social/email icons (Font Awesome)
- **Skills**: percentage skill bars for Web Design, HTML/CSS, Graphic Design and UI/UX
- **Our Portfolio**: project thumbnails with WEB / ALL / APPS / ICONS tabs
- **Get in Touch**: contact form (name, email, message) with a "Send Message" button
- Footer with social links (Facebook, LinkedIn, Twitter, Behance, Dribbble, GitHub)
- Responsive styles using media queries for tablet (up to 768px) and mobile (up to 428px) widths

## Tech Stack

| Technology | Usage |
| --- | --- |
| HTML5 | Page structure |
| CSS3 | Layout, styling and media queries (`css/index.css`) |
| Font Awesome 6.5.2 | Icons, loaded from the cdnjs CDN |

## Project Structure

```
Cuda/
├── index.html        # Main page
├── css/
│   └── index.css     # All styles, including responsive rules
├── assets/           # Logo, backgrounds, service icons, team photos, portfolio images
└── .vscode/
    └── settings.json # Live Server port (5501)
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
   cd Assignment/Cuda
   ```
3. Open `index.html` in your browser, or use the **Live Server** extension in VS Code (the project is configured for port `5501`). You can also run a static server:
   ```bash
   npx serve .
   ```

## Customization

- **Colors, fonts and spacing:** edit `css/index.css`.
- **Images and icons:** replace the files in `assets/`, keeping the same file names or updating the paths in `index.html`.
- **Text, team members and portfolio items:** edit the matching sections in `index.html`.

## Known Limitations

- Navigation, tab, portfolio and social links are placeholders (`href=""`) and do not point anywhere yet.
- The contact form has no backend or validation, so submitting it does nothing.
- The portfolio tabs (WEB / ALL / APPS / ICONS) are static and do not filter items.
- Section text is placeholder Lorem ipsum, and a few labels contain typos (for example "Deleopment" and "Beutiful") that you may want to fix.

## Author

**Aman Patil** – [@AmanPatil2002](https://github.com/AmanPatil2002)

## License

This project is for learning and assignment purposes. Add a license of your choice if you plan to share or reuse it.
