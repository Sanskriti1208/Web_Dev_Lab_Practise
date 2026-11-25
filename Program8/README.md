# P8 – Sticky Navbar and Card Overlay Using CSS Positioning

## 1. Aim

To create a webpage with a sticky navigation bar and an image card overlay using CSS positioning properties such as relative, absolute and sticky.

## 2. Procedure

1. Create an HTML file named `position.html`.
2. Start with the basic HTML structure using `<!DOCTYPE html>`, `<html>`, `<head>` and `<body>` tags.
3. Add a `<title>` tag to specify the webpage title.
4. Use the `<style>` tag to write CSS styling.
5. Create a navigation bar using the `<nav>` tag and add navigation links using the `<a>` tag.
6. Apply `position: sticky` and `top: 0` to make the navigation bar stick to the top while scrolling.
7. Create a card using a `<div>` element with the class `card`.
8. Add an image using the `<img>` tag and provide alternative text using the `alt` attribute.
9. Create another `<div>` with the class `overlay` to display text over the image.
10. Apply `position: relative` to the card and `position: absolute` to the overlay.
11. Use properties such as `bottom`, `left`, `z-index`, `width` and `background-color` to control the positioning and appearance.
12. Add additional content to make the webpage scrollable and test the sticky navigation bar.
13. Save the file and open it in a browser to view the output.

### HTML Elements and Tags Used

- **`<nav>`:** Defines the navigation section.
- **`<a>`:** Creates hyperlinks for navigation.
- **`<main>`:** Contains the main webpage content.
- **`<section>`:** Divides the webpage into different sections.
- **`<div>`:** Groups elements into containers.
- **`<img>`:** Displays an image.
- **`<h1>` and `<h2>`:** Define headings.
- **`<p>`:** Displays paragraphs.

### CSS Properties Used

- **`position: sticky`:** Makes an element stick to a specified position while scrolling.
- **`position: relative`:** Positions an element relative to its normal position and provides a reference for absolute children.
- **`position: absolute`:** Positions an element relative to its nearest positioned ancestor.
- **`top`, `bottom`, `left`, `right`:** Control the position of elements.
- **`z-index`:** Controls the stacking order of elements.
- **`background-color`:** Sets the background colour.
- **`rgba()`:** Creates colours with transparency.
- **`object-fit`:** Controls how an image fits inside its container.
- **`border-radius`:** Creates rounded corners.
- **`padding` and `margin`:** Control spacing inside and outside elements.

## 3. Observation

- The navigation bar remains visible at the top while scrolling because of sticky positioning.
- The card uses relative positioning as a reference for the overlay.
- The overlay is placed at the bottom of the image using absolute positioning.
- The `z-index` property controls the stacking order of elements.
- The use of transparent backgrounds makes the overlay text visible over the image.

## 4. Result

A webpage with a sticky navigation bar and an image card overlay was successfully created using CSS positioning properties.