This is a webpage I developed through the IBM full stack developer course on Coursera. The underlying structure of the webpage was already created, and I added modifications and fixed mistakes in the code to create a functional static webpage. 
# Personal Portfolio Website

A dynamic, single-page portfolio website built for **J. Brandon Fuller** featuring a retro, 8-bit aesthetic. This repository demonstrates core web development concepts by integrating HTML layout, custom CSS design, and Vanilla JavaScript DOM manipulation.

## Features

- **Responsive Navigation Structure:** A navigation bar mapped to anchored HTML ids for smooth scrolling to sections (`#about-me`, `#skills`, `#projects`, `#recommendations`).
- **Customized About Me:** A short developer bio complete with an 8-bit cartoon profile picture. 
- **Skills Grid:** A detailed flexbox layout listing languages and frameworks alongside custom SVG/PNG brand logos.
- **Project Showcase:** Highlights of unique developer projects styled using clean CSS cards. 
- **Dynamic Recommendations:** 
  - A viewing gallery for past recommendations.
  - A functional form at the bottom of the page allowing visitors to submit new recommendations. Submitting the form uses JavaScript to bind data, insert a new HTML block into the exact DOM tree via `appendChild()`, and immediately provides user-feedback through a modal pop-up dialogue (`showPopup(true)`).
- **Scroll to Top Widget:** A floating SVG action icon implemented to assist user experience.

## Technologies Used

- **HTML5**: Semantic tags, anchored lists, and script/stylesheet bindings.
- **CSS3**: Hover interactions, complex flex properties (`align-items`, `justify-content`, `wrap`), and absolute positioning elements.
- **JavaScript (ES6+)**: Document Object Model API traversal (`getElementById`, `createElement`).

## How to Run

1. Clone or download this folder to your local machine.
2. Inside your file explorer, simply double-click the `index.html` file to open it in your default, modern web browser (Google Chrome, Edge, Safari, Firefox).
3. To view live code changes, use an extension like **Live Server** in VS Code.

## Repository Structure

```text
/
├── html_finalprojimages/   # Local assets (logos, the 'Scroll to Top' SVG icon, etc.)
├── index.html              # Core application entry point
├── script.js               # Logic for form appending and modal handling
├── style.css               # Overall UI and presentation layer
└── README.md               # You are here
```
