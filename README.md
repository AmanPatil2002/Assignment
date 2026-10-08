# Assignment

A collection of front-end practice assignments built with plain **HTML**, **CSS** and **JavaScript**. The repository holds five static website projects, each in its own folder, plus a set of small JavaScript DOM exercises. There are no frameworks, build tools or backends, so every project runs by opening its HTML file in a browser.

## Projects

| Folder | Project | Description | Entry file |
| --- | --- | --- | --- |
| [`Be`](./Be) | Be – Agency Landing Page | Agency/portfolio page with About, Team, Service, Gallery, Blog and Contact sections | `index.html` |
| [`Cuda`](./Cuda) | Cuda – Creative Agency Landing Page | Web and mobile app agency page with services, team, skill bars, portfolio and a contact form | `index.html` |
| [`Gymtso-Fitnesss`](./Gymtso-Fitnesss) | Gymso Fitness – Gym Landing Page | Gym website with training classes, a weekly workout timetable, a contact form and an embedded map | `index.html` |
| [`Myntra`](./Myntra) | Myntra – Product Listing Page Clone | Clone of Myntra's Electronics listing page with menus, a filter sidebar, a product grid and a footer | `index.html` |
| [`Resto`](./Resto) | Resto – Restaurant Landing Page | Restaurant page with special dishes, a menu, team, testimonials and a reservation form | `resto.html` |
| [`javascript-question`](./javascript-question) | JavaScript Questions | Small DOM exercises: dynamic table rows, dropdown handling, text to speech, a progress bar and a digital clock | `1.html`, `2.html`, `3.html`, `7.html`, `8.html`, `9.html` |

Each folder has its own README with features, structure and known limitations.

## Tech Stack

| Technology | Usage |
| --- | --- |
| HTML5 | Page structure and forms |
| CSS3 | Layout, hover effects and responsive media queries |
| JavaScript (vanilla) | DOM manipulation, events, timers and the Web Speech API |
| Font Awesome 6.5.2 | Icons, loaded from the cdnjs CDN |

## Repository Structure

```
Assignment/
├── Be/                    # Agency landing page
├── Cuda/                  # Creative agency landing page
├── Gymtso-Fitnesss/       # Gym landing page
├── Myntra/                # Myntra product listing clone
├── Resto/                 # Restaurant landing page
├── javascript-question/   # JavaScript DOM exercises
├── index (1).html         # Basic HTML table practice page
└── style.css              # Bootstrap-style nav and search styles (practice file)
```

## Getting Started

### Prerequisites

A modern web browser. An internet connection is needed for the Font Awesome icons and the embedded map in the Gym project, which load from the web.

### Run locally

1. Clone the repository:
   ```bash
   git clone https://github.com/AmanPatil2002/Assignment.git
   ```
2. Go to the repository folder:
   ```bash
   cd Assignment
   ```
3. Open the entry file of any project in your browser (for example `Be/index.html`), or serve the whole repository with a static server:
   ```bash
   npx serve .
   ```
   Then open the folder of the project you want.

## Notes

- The files `index (1).html` and `style.css` in the repository root are loose practice files and are not linked to any project. `style.css` expects Bootstrap classes and an `images/search-icon.png` file that are not in the repository.
- The `Resto` project's main file is `resto.html` rather than `index.html`. Rename it if you want to publish it with GitHub Pages.
- The Gym project is based on a free Tooplate template, and the Myntra project is an unofficial clone for learning only. See each folder's README for details.

## Author

**Aman Patil** – [@AmanPatil2002](https://github.com/AmanPatil2002)

## License

This repository is for learning and assignment purposes. Add a license of your choice if you plan to share or reuse it, subject to the notes above.
