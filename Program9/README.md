# P9 – Responsive Navbar and Card Grid Using Flexbox

## 1. Aim

To create a responsive navigation bar and card grid layout using CSS Flexbox properties that automatically adjust according to different screen sizes.

## 2. Procedure

1. Create an HTML file named `flexbox.html`.
2. Start with the basic HTML structure using `<!DOCTYPE html>`, `<html>`, `<head>` and `<body>` tags.
3. Add the `<title>` tag to specify the webpage title.
4. Use the `<style>` tag to write CSS styling.
5. Create a navigation bar using the `<nav>` tag.
6. Add navigation links using the `<a>` tag and group them inside a `<div>` element.
7. Apply `display: flex` to arrange the navigation elements.
8. Use `justify-content: space-between` and `align-items: center` to align the navigation elements.
9. Create a card container using a `<div>` element with the class `card-container`.
10. Add individual cards using `<div>` elements with the class `card`.
11. Insert images using the `<img>` tag and add headings and descriptions using `<h2>` and `<p>` tags.
12. Apply Flexbox properties such as `display: flex`, `flex-wrap`, `justify-content` and `gap` to arrange the cards.
13. Use the `@media` query to make the webpage responsive on smaller screens.
14. Change the navigation and card layout using `flex-direction: column` for smaller screens.
15. Save the file and open it in a browser. Resize the browser window to test the responsive layout.

### HTML Elements and Tags Used

- **`<nav>`:** Defines the navigation section.
- **`<div>`:** Groups elements into containers.
- **`<a>`:** Creates navigation links.
- **`<main>`:** Contains the main webpage content.
- **`<h1>` and `<h2>`:** Define headings.
- **`<p>`:** Displays paragraphs.
- **`<img>`:** Displays images.
- **`<title>`:** Specifies the webpage title.
- **`<style>`:** Contains internal CSS styling.

### CSS Properties Used

- **`display: flex`:** Enables Flexbox layout.
- **`justify-content`:** Aligns items along the main axis.
- **`align-items`:** Aligns items along the cross axis.
- **`flex-wrap`:** Allows items to move to the next line.
- **`flex-direction`:** Sets the direction of items.
- **`gap`:** Adds spacing between items.
- **`padding`:** Adds space inside elements.
- **`margin`:** Adds space outside elements.
- **`background-color`:** Sets the background colour.
- **`border-radius`:** Creates rounded corners.
- **`object-fit`:** Controls how images fit inside containers.
- **`@media`:** Applies CSS styles based on screen size.

## 3. Observation

- Flexbox arranges navigation links and cards in a flexible layout.
- The `justify-content` and `align-items` properties help align elements.
- The `flex-wrap` property allows cards to move to the next row when space is insufficient.
- The `gap` property provides spacing between cards.
- Media queries change the layout for smaller screens.
- The webpage adjusts its layout according to different screen sizes.

## 4. Result

A responsive webpage with a Flexbox navigation bar and card grid was successfully created using CSS Flexbox and media queries.