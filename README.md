# Features

* **Simple & Clean Design:** Uses a minimalist dark theme for easy readability.
* **Responsive Layout:** Adapts to different screen sizes using CSS media queries (specifically for screens narrower than 600px).
* **Pure HTML & CSS:** Built entirely with standard HTML5 and CSS3. No JavaScript or external frameworks are used in this file.
* **Header Section:**
    * Displays name and a brief introduction/bio.
    * Includes contact information (email).
    * Provides quick links:
        * A styled button linking to an external portfolio (`https://mihaaaailai.github.io/Mihai.Grigore/`).
        * SVG icons linking to LinkedIn, GitHub, and Email (`mailto:`).
* **Thoughts Section:** A dedicated area to list articles or thoughts (currently contains one placeholder entry).
* **Projects Section:** Showcases selected projects with descriptions and links to their external repositories (GitHub).
* **Internal Styling:** All CSS is contained within `<style>` tags in the `<head>` section of the HTML file.

## File Structure

The entire website (as provided) consists of a single HTML file (likely intended to be named `index.html`).

* **`<head>`:** Contains meta tags (charset, viewport), the page title, and all the CSS rules within `<style>` tags.
* **`<body>`:** Contains the visible content, structured semantically using:
    * `div.container`: Wraps the main content for centering and max-width.
    * `<header>`: Includes `div.intro` for text and `div.links` for the portfolio button and social icons.
    * `<section id="thoughts">`: Holds blog post summaries/links.
    * `<section id="projects">`: Holds project summaries/links.
    * `<footer>`: Contains the copyright notice.

## Viewing the Page

1.  Clone or download this repository/file.
2.  Open the `.html` file (e.g., `index.html`) directly in your web browser (like Chrome, Firefox, Safari, Edge).

## Customization

To adapt this page for your own use:

1.  **Content:**
    * Edit the text content directly within the HTML tags (e.g., `<h1>`, `<p>`). Change the name, bio, project descriptions, thought titles, footer copyright year, etc.
    * Update the email address in the intro paragraph and the `mailto:` link.
2.  **Links:**
    * Modify the `href` attributes in the `<a>` tags within the `<div class="links">` to point to your own portfolio, LinkedIn, GitHub, and email.
    * Update the `href` attributes for the project links in the `#projects` section.
    * Update the `href` for the "Thoughts" entries and potentially create the linked `.html` files (like `beyond-code-completion.html`) or link to external blog posts. *Note: The current "Thoughts" entry has a future date (Apr 12, 2025).*
3.  **Styling:**
    * Adjust the CSS rules within the `<style>` tags in the `<head>` to change colors, fonts, spacing, layout, etc. Key selectors include `body`, `.container`, `header`, `.links`, `.portfolio-button`, `#thoughts`, `#projects`.

## Technologies Used

* HTML5
* CSS3 (including Flexbox and Media Queries)
* Inline SVG (for icons)

---
