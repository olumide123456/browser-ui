

# Browser Ui

## Overview

This project creates a responsive grid layout with interactive toggle switches. It's built using HTML, CSS, and JavaScript to display a 4x3 grid of items, each containing a logo, a brief explanation, a "remove" text, and a toggle switch.

## Features

*   **Responsive Grid Layout:** The grid adapts to different screen sizes, ensuring a consistent look and feel across devices.
*   **Interactive Toggle Switches:** Each grid item includes a toggle switch that users can click or use the keyboard (Enter or Space) to activate or deactivate.
*   **Simple and Clean Design:** The project uses a minimalist design with a dark grey background for each grid cell and clear, readable text.
*   **Accessibility:** The toggle switches are implemented with accessibility in mind, using ARIA attributes to provide proper context for screen readers.

## Technologies Used

*   HTML5
*   CSS3
*   JavaScript

## Structure

The project structure is as follows:

*   `well.html`: Contains the HTML markup for the grid layout and toggle switches.
*   `well.css`: Contains the CSS styles for the grid layout and toggle switches.
*   `well.js`: Contains the JavaScript code for handling the toggle switch functionality.

## HTML Structure

The `well.html` file is structured as follows:

*   A `<head>` section containing metadata, CSS styles, and the page title.
*   A `<body>` section containing the grid layout and JavaScript code.
*   The grid layout is created using a `<div class="grid-container">` element.
*   Each grid item is a `<div class="grid-item">` element, containing:
    *   A `<div class="content">` element with a logo and a brief explanation.
    *   A `<div class="bottom-row">` element with a "remove" text and a toggle switch.
*   The toggle switch is a `<div class="toggle">` element with ARIA attributes for accessibility.

## CSS Styling

The css style is on a different file, but its called in the html. `well.html`

*   Basic styling for the `body` element, including font and background color.
*   Styles for the `.grid-container` to create the grid layout using `display: grid`.
*   Styles for the `.grid-item` to set the background color, padding, and flex layout.
*   Styles for the `.content` to align the logo and text.
*   Styles for the `.logo` to create a placeholder logo.
*   Styles for the `.text` to format the brief explanation.
*   Styles for the `.bottom-row` to align the "remove" text and toggle switch.
*   Styles for the `.toggle` to create the toggle switch appearance and handle the active state.

## JavaScript Functionality

The JavaScript code is in a different file but its called in the html code, and handles the toggle switch functionality:

*   An event listener is added to each `.toggle` element to toggle the `active` class on click.
*   The `aria-checked` attribute is updated based on the toggle state for accessibility.
*   Keyboard support is added to toggle the switch using the Enter or Space key.

## How to Use

1.  Clone the repository to your local machine.
2.  Open the `well.html` file in your web browser.

## Customization

*   Modify the content of the `.text` elements to change the brief explanations.
*   Replace the placeholder logos with your own images or icons.
*   Adjust the CSS styles to customize the appearance of the grid and toggle switches.
*   Extend the JavaScript code to add additional functionality, such as saving the toggle state or performing actions based on the toggle state.

## Accessibility

The toggle switches are implemented with accessibility in mind, using the following ARIA attributes:

*   `role="switch"`: Indicates that the element is a toggle switch.
*   `aria-checked="false"`: Indicates the initial state of the toggle switch (false = off).
*   `aria-label="Toggle"`: Provides a label for the toggle switch for screen readers.

Keyboard support is also provided, allowing users to toggle the switch using the Enter or Space key.





