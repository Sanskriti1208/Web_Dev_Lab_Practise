# P10 – Portfolio Header and Footer with Advanced Flexbox

## 1. Aim

To design a responsive portfolio webpage with a header and footer using advanced CSS Flexbox properties for proper alignment, spacing and layout.

## 2. Procedure

1. Create an HTML file named `portfolio.html`.
2. Start with the basic HTML structure using `<!DOCTYPE html>`, `<html>`, `<head>` and `<body>` tags.
3. Add the `<title>` tag to specify the webpage title.
4. Use the `<style>` tag to write CSS styling.
5. Create a header using the `<header>` tag.
6. Add a logo using a `<div>` element and navigation links using the `<nav>` and `<a>` tags.
7. Add a Contact Me link and group the header elements inside a container.
8. Apply `display: flex`, `justify-content: space-between` and `align-items: center` to arrange the header elements.
9. Create the main content using the `<main>` tag with headings and paragraphs.
10. Create a footer using the `<footer>` tag.
11. Divide the footer into sections using `<div>` elements with the class `footer-section`.
12. Apply `display: flex`, `flex: 1`, `gap` and `flex-wrap` to arrange the footer sections.
13. Use the `@media` query to make the header and footer responsive on smaller screens.
14. Change the layout to a column using `flex-direction: column` for smaller screens.
15. Save the file and open it in a browser to view the output.

### HTML Elements and Tags Used

- **`<header>`:** Defines the top section of the webpage.
- **`<nav>`:** Creates the navigation section.
- **`<a>`:** Creates hyperlinks.
- **`<div>`:** Groups related elements into containers.
- **`<main>`:** Contains the main webpage content.
- **`<h1>` and `<h3>`:** Define headings.
- **`<p>`:** Displays paragraphs.
- **`<footer>`:** Defines the bottom section of the webpage.

### CSS Properties Used

- **`display: flex`:** Enables Flexbox layout.
- **`justify-content`:** Aligns items along the main axis.
- **`align-items`:** Aligns items along the cross axis.
- **`flex-wrap`:** Allows items to move to the next line.
- **`flex-direction`:** Changes the direction of items.
- **`flex: 1`:** Allows an element to grow and share available space.
- **`gap`:** Adds spacing between elements.
- **`min-width`:** Sets the minimum width of an element.
- **`padding`:** Adds space inside elements.
- **`margin`:** Adds space outside elements.
- **`text-align`:** Aligns text.
- **`border-top`:** Adds a border to the top of an element.
- **`@media`:** Applies CSS styles based on screen size.

## 3. Observation

- Flexbox is used to arrange the logo, navigation links and contact button in the header.
- The `justify-content` property distributes available space between elements.
- The `align-items` property aligns elements vertically.
- The `flex: 1` property allows footer sections to share available space.
- The `flex-wrap` property prevents content from overflowing.
- Media queries change the layout for smaller screens.
- The webpage displays a responsive header and footer.

## 4. Result

A responsive portfolio webpage with an advanced Flexbox header and footer was successfully created using CSS Flexbox properties and media queries.