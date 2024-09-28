# Website Interaction Features

This project contains JavaScript code that adds interactive functionalities to a webpage, such as modal windows, smooth scrolling, tabbed components, sticky navigation, lazy loading of images, and a slider component. The code is designed to enhance the user experience by making the webpage more dynamic and responsive to user actions.

## Table of Contents

- [Features](#features)
  - [Modal Window](#modal-window)
  - [Smooth Scrolling](#smooth-scrolling)
  - [Tabbed Component](#tabbed-component)
  - [Menu Fade Animation](#menu-fade-animation)
  - [Sticky Navigation](#sticky-navigation)
  - [Reveal Sections](#reveal-sections)
  - [Lazy Loading Images](#lazy-loading-images)
  - [Slider Component](#slider-component)
- [How to Use](#how-to-use)
- [License](#license)

## Features

### Modal Window

The modal window feature allows the user to open a modal by clicking on specific buttons and close it either by clicking the close button, the overlay, or pressing the `Escape` key.

- **Opening the modal**: Clicking on a button with the class `.btn--show-modal`.
- **Closing the modal**: Clicking on the close button, overlay, or pressing the `Escape` key.

### Smooth Scrolling

The code implements smooth scrolling for navigation links and a button that scrolls to a specific section of the page.

- **Scroll to section**: Clicking on the button with class `.btn--scroll-to` will smoothly scroll to `#section--1`.
- **Navigation links**: Clicking on any navigation link will smoothly scroll to the corresponding section of the page.

### Tabbed Component

The tabbed component allows users to switch between different content panels by clicking on tabs.

- **Switching tabs**: Clicking on a tab within the `.operations__tab-container` will activate the corresponding content panel.

### Menu Fade Animation

This feature creates a fade effect when hovering over navigation links, dimming the non-hovered links and the logo.

- **Hover effect**: When hovering over a navigation link, the other links and the logo will fade out, providing a subtle visual cue.

### Sticky Navigation

The navigation bar becomes "sticky" (fixed at the top of the page) when the user scrolls past the header section.

- **Sticky behavior**: The navigation bar with the `.nav` class becomes sticky once the header section is no longer visible.

### Reveal Sections

Sections of the webpage are initially hidden and are revealed as the user scrolls down the page.

- **Reveal on scroll**: As the user scrolls, sections with the `.section` class are revealed once they come into view.

### Lazy Loading Images

Images on the page are lazy-loaded, meaning they are only loaded when they come into the viewport, improving initial page load time.

- **Lazy-loading behavior**: Images with the `data-src` attribute are loaded as they enter the viewport, and once loaded, the placeholder low-resolution image is replaced with the high-resolution image.

### Slider Component

A slider component that allows users to navigate through slides either via buttons or keyboard, with indicators (dots) for each slide.

- **Navigation**: Users can navigate through slides using the left and right arrow buttons or by pressing the `ArrowLeft` and `ArrowRight` keys.
- **Dots navigation**: Clicking on a dot navigates the user to the corresponding slide.

## How to Use

1. **HTML Structure**: Ensure that your HTML file contains the appropriate structure, including elements with classes such as `.modal`, `.overlay`, `.btn--show-modal`, `.nav`, `.operations__tab-container`, `.section`, `.slider`, and others referenced in the JavaScript file.
   
2. **Include the Script**: Add the provided JavaScript code at the bottom of your HTML file or link to it as an external file.

```html
<script src="path/to/your/script.js"></script>
```

3. **CSS Styling**: Ensure that your CSS file includes styles for the hidden and active states of the modal, tabs, sections, and other elements. Example class names that should be styled:
   - `.hidden`: For hiding elements like the modal and overlay.
   - `.sticky`: To set the fixed position of the navigation bar.
   - `.section--hidden`: To hide sections initially.
   - `.lazy-img`: For lazy-loaded images.
   - `.operations__tab--active` and `.operations__content--active`: For active tab content.
   - `.dots__dot`, `.dots__dot--active`: For slider dots and their active state.

4. **Customizing**: You can modify the class names or functionality as needed to suit your project.

or Visit : https://bankist-website-eg.netlify.app
