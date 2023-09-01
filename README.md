# Cafe Menu

## Hosted Link
[Click here to view the hosted page](https://saifulislam05.github.io/cafe-menu/)


## UI 
![image](https://github.com/saifulislam05/css-assign/assets/73392705/1776e456-e4ce-466f-b7c6-44127f5f1854)

## Explanation of some tags

### `<link>` Tag
The `<link>` tag is used to connect the external CSS file (`styles.css`) with the HTML file. The `href` attribute specifies the path to the CSS file.

### `<img>` Tag
The `<img>` tag is used to display the logo and item images. The `src` attribute points to the image's URL. The images are centered using `margin-left` and `margin-right` set to `auto`.

## Styles Explanation

### `body` Selector:
- `background-image: url(...)`: Sets the background image of the entire page to the provided URL.
- `font-family: sans-serif;`: Applies the "sans-serif" font family to all text within the page.
- `padding: 20px;`: Adds 20 pixels of padding to all sides of the page content.

### `h1` Selector:
- `font-size: 40px;`: Sets the font size of all main headings `<h1>` to 40 pixels.
- `margin-top: 0;`: Removes the default top margin of main headings.
- `margin-bottom: 15px;`: Adds 15 pixels of margin at the bottom of main headings.

### `h2` Selector:
- `font-size: 30px;`: Sets the font size of all subheadings `<h2>` to 30 pixels.

### `.established` Class Selector:
- `font-style: italic;`: Applies italic style to elements with the class `.established`.

### `h1`, `h2`, `p` Selectors:
- `text-align: center;`: Centers the alignment of text within main headings, subheadings, and paragraphs.

### `.menu` Class Selector:
- `width: 80%;`: Sets the width of elements with class `.menu` to 80% of their containing element.
- `background-color: burlywood;`: Applies a burlywood background color to elements with class `.menu`.
- `margin-left: auto; margin-right: auto;`: Centers elements with class `.menu` horizontally using auto margins.
- `padding: 20px;`: Adds 20 pixels of padding to elements with class `.menu`.
- `max-width: 500px;`: Limits the maximum width of elements with class `.menu` to 500 pixels.

### `img` Selector:
- `display: block;`: Sets images to display as block-level elements, allowing for margin manipulation.
- `margin-left: auto; margin-right: auto;`: Centers images horizontally within their container.
- `margin-top: -25px;`: Adjusts the top margin of images by -25 pixels.

### `hr` Selector:
- `height: 2px;`: Sets the height of horizontal lines `<hr>` to 2 pixels.
- `background-color: brown;`: Applies a brown background color to horizontal lines.
- `border-color: brown;`: Sets the border color of horizontal lines to brown.

### `.bottom-line` Class Selector:
- `margin-top: 25px;`: Adds 25 pixels of margin at the top for elements with class `.bottom-line`.

### Font Styling:
- Different font sizes and families are used to style headings and paragraphs, creating visual hierarchy.

### `.item p` Selector:
- `display: inline-block;`: Makes paragraphs inside elements with class `.item` inline-block elements.
- `margin-top: 5px; margin-bottom: 5px;`: Adds 5 pixels of margin at the top and bottom of paragraphs.
- `font-size: 18px;`: Sets the font size of paragraphs inside `.item` to 18 pixels.

### `.flavor`, `.dessert` Class Selectors:
- `text-align: left;`: Aligns text to the left within elements with classes `.flavor` and `.dessert`.
- `width: 75%;`: Sets the width of elements with classes `.flavor` and `.dessert` to 75% of their container.

### `.price` Class Selector:
- `text-align: right;`: Aligns text to the right within elements with class `.price`.
- `width: 25%;`: Sets the width of elements with class `.price` to 25% of their container.

### Footer Styling:
- Font size and margin adjustments for the footer section.

### Links Styling:
- `a`, `a:visited`, `a:hover`, and `a:active` selectors modify link styles for different states.
