# Gymso Fitness – Gym Landing Page

A static, single-page website for a fictional gym, **Gymso Fitness**. It is built with plain **HTML5** and **CSS3**, with no build step, framework or backend. It is a front-end practice assignment focused on page layout, a weekly timetable and responsive styling.

![Gymso Fitness preview](Gymso%20Fitness.png)

## Features

- Hero section with navigation, social icons and "GET STARTED" / "LEARN MORE" buttons
- Membership offer banner and **working hours** panel
- **About Us** section with a welcome message and trainer cards (Mary Yan, Catherine)
- **Our Training Classes**: Yoga, Aerobic and Cardio cards with trainer name and price
- **Workout Timetable**: weekly schedule table (Mon–Sat) with class names and time slots
- **Contact form** (name, email, message) and an embedded Google Map showing the gym location
- Footer with copyright, email and phone details
- Responsive styles using media queries for tablet (up to 768px) and mobile (up to 428px) widths

## Tech Stack

| Technology | Usage |
| --- | --- |
| HTML5 | Page structure |
| CSS3 | Layout, styling and media queries (`css/index.css`) |
| Font Awesome 6.5.2 | Icons, loaded from the cdnjs CDN |
| Google Maps embed | Location map (iframe) |

## Project Structure

```
Gymtso-Fitnesss/
├── index.html          # Main page
├── css/
│   └── index.css       # All styles, including responsive rules
├── assets/             # Hero background, class images and trainer/team photos
└── Gymso Fitness.png   # Screenshot / design preview
```

## Getting Started

### Prerequisites

A modern web browser. An internet connection is needed for the Font Awesome icons and the embedded map.

### Run locally

1. Clone the repository:
   ```bash
   git clone https://github.com/AmanPatil2002/Assignment.git
   ```
2. Go to the project folder:
   ```bash
   cd Assignment/Gymtso-Fitnesss
   ```
3. Open `index.html` in your browser, or use a static server, for example:
   ```bash
   npx serve .
   ```

## Customization

- **Colors, fonts and spacing:** edit `css/index.css`.
- **Images:** replace the files in `assets/`, keeping the same file names or updating the references in the CSS and HTML.
- **Classes, prices, timetable and opening hours:** edit the matching sections in `index.html`.
- **Map location:** replace the `src` of the `<iframe>` in the "Where you can find us" section with your own Google Maps embed link.

## Known Limitations

- Navigation, button and social links are placeholders (`href=""`) and do not point anywhere yet.
- The contact form has no backend or validation, so submitting it does nothing.
- The class images are set through CSS backgrounds, so they will not show if the paths in `css/index.css` are changed or the `assets/` folder is moved.
- Some text is placeholder Lorem ipsum, and a few labels contain typos (for example "menber") that you may want to fix.
- The folder name is spelled "Gymtso-Fitnesss", while the site itself says "Gymso Fitness".

## Credits

The design comes from the free **Gymso Fitness** HTML template by [Tooplate](https://www.tooplate.com/), as noted on the page. The template's own text allows personal or business use but not redistributing it on template collection sites. Please keep that in mind if you publish or share this project.

## Author

**Aman Patil** – [@AmanPatil2002](https://github.com/AmanPatil2002)

## License

This project is for learning and assignment purposes. Add a license of your choice if you plan to share or reuse it, subject to the Tooplate template terms above.
