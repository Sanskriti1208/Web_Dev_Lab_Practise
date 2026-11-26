# P11 – Newspaper-Style Three-Column Layout with CSS Grid

## 1. Aim

To design a newspaper-style webpage using CSS Grid with a three-column layout containing a main headline and multiple news articles.

## 2. Procedure

1. Create an HTML file named `newspaper.html`.
2. Start with the basic HTML structure using `<!DOCTYPE html>`, `<html>`, `<head>` and `<body>` tags.
3. Add the `<title>` tag to specify the webpage title.
4. Use the `<style>` tag to write CSS styling.
5. Create a header using the `<header>` tag to display the newspaper name and description.
6. Create a main content container using the `<main>` tag with the class `container`.
7. Apply `display: grid` to enable CSS Grid layout.
8. Use `grid-template-columns: repeat(3, 1fr)` to create three equal columns.
9. Use `gap` to add spacing between the grid items.
10. Create a main headline using the `<section>` tag with the class `headline`.
11. Apply `grid-column: 1 / 4` to make the headline span across all three columns.
12. Create individual news articles using the `<article>` tag.
13. Add images using the `<img>` tag and descriptions using heading and paragraph tags.
14. Apply CSS properties such as `padding`, `background-color`, `border-radius` and `object-fit` to style the articles.
15. Use the `@media` query to change the layout into a single column on smaller screens.
16. Create a footer using the `<footer>` tag.
17. Save the file and open it in a browser to view the output.

### HTML Elements and Tags Used

- **`<header>`:** Defines the top section containing the newspaper name.
- **`<main>`:** Contains the main content of the webpage.
- **`<section>`:** Groups the main headline content.
- **`<article>`:** Defines independent news articles.
- **`<img>`:** Displays images.
- **`<h1>` and `<h2>`:** Define headings.
- **`<p>`:** Displays paragraphs.
- **`<footer>`:** Defines the bottom section of the webpage.

### CSS Properties Used

- **`display: grid`:** Enables CSS Grid layout.
- **`grid-template-columns`:** Defines the number and size of columns.
- **`grid-template-rows`:** Defines the size of rows.
- **`repeat()`:** Repeats column or row sizes.
- **`fr`:** Represents a fraction of the available space.
- **`grid-column`:** Specifies how many columns an element occupies.
- **`gap`:** Adds spacing between grid items.
- **`object-fit`:** Controls how images fit inside their containers.
- **`padding`:** Adds space inside elements.
- **`margin`:** Adds space outside elements.
- **`background-color`:** Sets the background colour.
- **`border-radius`:** Creates rounded corners.
- **`@media`:** Applies CSS styles based on screen size.

## 3. Observation

- CSS Grid is used to arrange the newspaper content into three equal columns.
- The `grid-template-columns` property defines the column structure.
- The `repeat()` function creates equal-sized columns.
- The `grid-column` property allows the main headline to span across all three columns.
- The `gap` property provides spacing between articles.
- Media queries change the three-column layout into a single-column layout on smaller screens.

## 4. Result

A newspaper-style webpage with a three-column layout was successfully created using CSS Grid and media queries.