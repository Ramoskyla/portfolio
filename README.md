# Simple Accessible Portfolio (HTML + CSS)

**Purpose**  
A single-page portfolio demonstrating semantic HTML, accessible patterns, maintainable CSS, and a responsive layout. Built to meet the lab requirements: `index.html`, `css/styles.css`, `assets/`, and `README.md`. (See lab brief provided with the assignment.)

**How to open**  
1. Clone or download the folder.  
2. Open `index.html` in a browser, or run a local server:
   - `python3 -m http.server 8000` then visit `http://localhost:8000`.

**Accessibility notes**  
- Skip link allows keyboard users to jump to content.  
- All images (profile picture) contain meaningful `alt` attributes.  
- Focus outlines are preserved and enhanced (no `outline: none`).  
- Color palette and text sizing chosen for good contrast and readability.  
- HTML uses semantic landmarks (`header`, `main`, `section`, `footer`) and a proper heading order (one `h1`, `h2` for sections, `h3` for project titles).

**Validation**  
- HTML: Validate at https://validator.w3.org/nu/  
- CSS: Validate at https://jigsaw.w3.org/css-validator/

**Notes**  
- Replace the profile picture in `/assets` with your own optimized image.  
- Project cards do not use images anymore (text-only for simplicity).  
- Replace text placeholders (Your Name, email, project descriptions) with your content.
