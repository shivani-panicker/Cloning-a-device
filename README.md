# Netflix Clone

This repository contains the code for a Netflix clone landing page with various sections, such as registration, features, FAQ, and footer. It closely mimics the UI of Netflix with custom styling, interactive elements, and smooth scrolling.

## Table of Contents

- [Description](#description)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Credits](#credits)

## Description

The project replicates the user interface (UI) of Netflix's landing page, particularly focusing on the registration and feature presentation sections. It is designed using basic web technologies like HTML, CSS, and JavaScript. This landing page showcases Netflix’s essential features such as sign-up, movie/TV show availability across devices, and the ability to watch offline.

The page includes:
- A **registration form** asking users to input their email address to start the Netflix membership.
- **Sections showcasing Netflix features**, like watching on TV, mobile devices, offline watching, and creating profiles for kids.
- **Frequently Asked Questions (FAQ)** section with interactive, collapsible answers.
- **Footer section** with links to Netflix-related pages and customer support details.
- A **Back to Top button** for easy navigation.

## Features

- **Responsive Design**: The page is fully responsive, meaning it adjusts dynamically for different screen sizes. Whether you're viewing it on a desktop, tablet, or mobile, the layout will look great.
- **Interactive FAQ Section**: Users can click on a question in the FAQ section to toggle between showing and hiding the answer. This is achieved using simple JavaScript to show/hide content on button click.
- **Smooth Scrolling**: A floating "Back to Top" button allows users to smoothly scroll back to the top of the page, making navigation user-friendly.
- **Multimedia Support**: Video backgrounds are used to showcase Netflix's features, such as watching on different devices or downloading content for offline viewing.
- **Footer Links**: A section at the bottom of the page includes various helpful links such as "Investor Relations", "Help Centre", and other Netflix-related resources.
  
## Installation

To clone and set up the project on your local machine, follow these steps:

1. **Clone the repository** to your local machine using the following command:
    ```bash
    git clone https://github.com/yourusername/netflix-clone.git
    ```

2. **Navigate to the project directory**:
    ```bash
    cd netflix-clone
    ```

3. **Open the project** in a browser:
   - You can open the `index.html` file directly in any modern web browser (Google Chrome, Firefox, Safari, etc.):
   - If you're using macOS, for example:
    ```bash
    open index.html
    ```
    - If you're on Windows, just double-click the `index.html` file, and it will open in your default browser.

You can also use any local development server (such as [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) in VSCode) to view the page dynamically as you make changes.

## Usage

This project contains three main components:

1. **HTML (`index.html`)**:
   - This file contains the overall structure of the landing page. It includes the navigation bar, sign-up section, feature presentation areas, FAQ, and footer.
   - The FAQ section uses `<button>` elements for collapsible question/answer interactions, and `<video>` and `<img>` tags to display the multimedia content.

2. **CSS (`style.css`)**:
   - This file holds all the styles for the landing page, including:
     - **Layout styles** (grid, flexbox, etc.) for responsiveness.
     - **Typography settings** (fonts, sizes, weights).
     - **Background and color styles**, including images for various sections.
     - Media queries for responsive design on different screen sizes.
   
3. **JavaScript (within `index.html`)**:
   - This script handles the interactive FAQ section. It listens for clicks on the FAQ questions and toggles the visibility of the answers.
   - It also provides smooth scroll functionality for the "Back to Top" button. The JavaScript ensures that when the user clicks on this button, the page smoothly scrolls back to the top of the page.

## Credits

- This project is based on Netflix's landing page design.
- **Fonts**: The fonts are sourced from [Google Fonts](https://fonts.google.com/), specifically the 'Poppins' and 'Martel Sans' fonts for modern typography.
- **Interactive FAQ Section**: JavaScript is used to toggle the FAQ questions and answers, providing a smooth user experience.
- **Icons**: Simple SVG arrows are used in the FAQ section to indicate whether a question's answer is expanded or collapsed.

## License

This project is open-source and available under an **MIT License**. If you would like to contribute or modify the project, you can freely do so. However, you are responsible for checking the copyright laws and respecting intellectual property if you decide to deploy or distribute the project in any form.
