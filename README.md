# Masonry Image Gallery

This project is a beautiful and responsive masonry-style image gallery built with pure HTML and CSS. It was created as part of a Quera Bootcamp.

## Project Overview

The Masonry Image Gallery is a single-page website that showcases a collection of images in a dynamic, staggered grid layout. This type of layout is often called "masonry" because it resembles a stone wall with irregularly sized stones.

This project is an excellent example of how to create a complex and visually appealing layout using modern CSS features like CSS Grid.

## Features

*   **Masonry layout:** The images are arranged in a multi-column layout with a staggered effect, similar to Pinterest.
*   **Responsive design:** The gallery is responsive and will adapt to different screen sizes.
*   **Hover effect:** The images have a subtle hover effect that lifts them up, adding a nice touch of interactivity.
*   **Pure CSS:** The entire layout is achieved with CSS, without the need for any JavaScript.

## Technologies Used

*   **HTML:** For the structure and content of the website.
*   **CSS:** For the styling and the masonry layout (using CSS Grid).

## How to View

To view this website, you can simply open the `index.html` file in your web browser.

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/init050/gallery-html-css.git
    cd front/gallery
    ```

2.  **Open in your browser:**
    Open the `index.html` file directly in your web browser.

## How It Works

The masonry effect is created using CSS Grid. The `.masonry` container is set to `display: grid`, and the `grid-template-columns` property is used to create a responsive number of columns. The `grid-auto-rows` property is set to a small value to create a fine-grained grid.

The individual `.item` elements are then manually placed on the grid using the `grid-row: span` property to make them different heights.

## Future Improvements

*   **Dynamic content:** The images are currently hardcoded in the HTML. The project could be improved by loading the images dynamically from a JavaScript array or an API.
*   **Lightbox effect:** Add a lightbox feature so that when you click on an image, it opens in a full-screen overlay.
*   **Infinite scroll:** Implement an infinite scroll feature to load more images as the user scrolls down the page.
*   **Improved responsiveness:** While the gallery is responsive, the manual row spans could be adjusted with media queries to create a more optimized layout for different screen sizes.
