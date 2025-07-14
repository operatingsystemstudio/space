# Operating System Studio

## Overview
This project is a web-based application called "Operating System Studio." It features a dynamic background slideshow that cycles through six images, applying visual effects such as inversion and black-and-white filters. The application is designed to provide an engaging user experience with smooth transitions between images.

## Project Structure
```
space
├── assets
│   ├── 3-2
│   │   ├── 1.jpg
│   │   ├── 2.jpg
│   │   ├── 3.jpg
│   │   ├── 4.jpg
│   │   ├── 5.jpg
│   │   └── 6.jpg
│   └── suisse
│       ├── SuisseIntl-Regular.woff2
│       ├── SuisseIntl-Black.woff2
│       └── SuisseIntl-Medium.woff2
├── index.html
├── style.css
├── script.js
└── README.md
```

## Files Description
- **index.html**: Contains the main structure of the web page, including links to stylesheets and scripts, as well as the HTML elements for displaying the title and links.
  
- **style.css**: Defines the CSS styles for the project, including layout, font styles, and visual effects for the elements on the page.

- **script.js**: Contains the JavaScript code that handles the image slideshow functionality. It automatically changes the background image every 4 seconds, applies invert and black-and-white effects, and implements a transition effect using luma key and a blurred effect. Users can click to switch to a non-inverted, color mode.

- **assets/3-2**: Directory containing the six images (1.jpg to 6.jpg) used in the slideshow.

- **assets/suisse**: Directory containing the font files used in the project.

## Setup Instructions
1. Clone the repository to your local machine.
2. Open the `index.html` file in a web browser to view the application.
3. Ensure that all assets are correctly linked and available in the specified directories.

## Functionality
- The background image will automatically change every 4 seconds.
- Images will initially display with invert and black-and-white effects.
- A transition effect will be applied during image changes.
- Clicking on the background will switch to a non-inverted, color mode.