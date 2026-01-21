# ☕ Camper Cafe Menu - ![Status](https://img.shields.io/badge/status-completed-green)

This project is a responsive menu for a cafe, created as part of the **freeCodeCamp Responsive Web Design** curriculum. It focuses on the clean separation of content (HTML) and design (CSS).

## 🛠 Technologies
* **HTML5:** Semantic structuring using `<main>`, `<section>`, `<article>`, and `<footer>`.
* **CSS3:** Layout design using `inline-block`, Google Fonts integration, custom properties, and responsive design techniques.

## 🚀 Features
* **Responsive Layout:** The menu automatically adjusts to different screen sizes (centered with a `max-width` of 500px).
* **Interactive Elements:** Styled hover states for links in the footer section.
* **Authentic Typography:** Utilization of *Impact* for headings and *Serif* for body text to create a professional cafe aesthetic.
* **Pixel-Perfect Alignment:** Precise alignment of prices and items by solving the "whitespace issue" inherent to inline elements.

## 🧠 The Process
The primary focus was the **CSS Box Model**. I learned how to horizontally center elements using `margin-left: auto` and `margin-right: auto`. A specific challenge was the behavior of `display: inline-block`: to achieve an exact width of 75% and 25% on the same line, the HTML tags had to be written without spaces (`</p><p>`), as browsers interpret line breaks in code as physical gaps.

### ⚠️ Accessibility Note
Please note that this is a pure CSS layout exercise focused on positioning, the box model, and styling. As such, web accessibility (A11y) best practices (like semantic list structures for menu items or high-contrast ratios) were not the primary focus of this specific challenge. Improving accessibility would be the next logical step for a production-ready version of this menu.

## 💻 Running the Project
Since this is a static website, no installation is required:
1. Clone the repository: `git clone https://github.com/rkaus-dev/fcc-cafe-menu.git`
2. Open the `index.html` file directly in your preferred web browser.

## 🖼 Preview


### Quick Links
[Live Demo](https://rkaus.dev)
