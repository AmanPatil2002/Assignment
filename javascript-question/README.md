# JavaScript Questions

A collection of small, standalone **HTML + JavaScript** practice exercises. Each file is a self-contained page (HTML, CSS and JavaScript in one file) that demonstrates a common DOM-manipulation task. There are no dependencies, no build step and no backend, so every example runs by opening the file in a browser.

## Exercises

| File | Exercise | What it demonstrates |
| --- | --- | --- |
| `1.html` | Add rows to a table dynamically | `insertRow`, `insertCell`, `createElement`; each new row gets a row number and text inputs |
| `2.html` | Remove items from a dropdown list | Removing the selected `<option>` from a `<select>` with `remove(selectedIndex)` |
| `3.html` | Show the selected dropdown value | Reading the chosen option in an `onchange` handler and showing it in a text box |
| `7.html` | Text to Speech converter | Browser Web Speech API (`speechSynthesis`), input validation and a styled gradient UI |
| `8.html` | Animated progress bar | `setInterval` and updating an element's width until it reaches 100% |
| `9.html` | Digital clock | `Date`, `setInterval`, 12-hour AM/PM formatting and zero-padding |

> The numbering skips `4`, `5` and `6`; those exercises are not in this folder.

## Tech Stack

| Technology | Usage |
| --- | --- |
| HTML5 | Page structure and form controls |
| CSS3 | Inline `<style>` blocks for layout and styling |
| JavaScript (vanilla) | DOM manipulation, events, timers and the Web Speech API |
| Google Fonts (Poppins) | Font for the Text to Speech page (`7.html`), loaded from the web |

## Project Structure

```
javascript-question/
├── 1.html   # Add table rows
├── 2.html   # Remove dropdown items
├── 3.html   # Dropdown selection
├── 7.html   # Text to Speech converter
├── 8.html   # Progress bar
└── 9.html   # Digital clock
```

## Getting Started

### Prerequisites

A modern web browser. The Text to Speech page (`7.html`) works best in Chrome, Edge or Safari, which support the Web Speech API, and needs an internet connection for the Poppins font.

### Run locally

1. Clone the repository:
   ```bash
   git clone https://github.com/AmanPatil2002/Assignment.git
   ```
2. Go to the folder:
   ```bash
   cd Assignment/javascript-question
   ```
3. Open any exercise (for example `1.html`) directly in your browser, or use a static server:
   ```bash
   npx serve .
   ```

## Known Limitations

- `9.html`: at midnight the 12-hour conversion has a bug (`hr = 12` is assigned instead of `hour = 12`), so the clock shows `00` instead of `12`. The time and AM/PM text are also joined without a space (for example `08:10:45AM`).
- `1.html`: the table borders use the color `#fefefe`, which is almost white, so they are barely visible on a white background.
- `3.html`: the label says "Your selected tutorial site" even though the dropdown is about sports, and the heading contains the typo "Select you favourite".
- `7.html`: the button text always resets to "Play Converted Sound" after 5 seconds, even if the speech is still playing.
- `8.html`: the page `<title>` is still the default "Document".

## Author

**Aman Patil** – [@AmanPatil2002](https://github.com/AmanPatil2002)

## License

This project is for learning and practice purposes. Add a license of your choice if you plan to share or reuse it.
