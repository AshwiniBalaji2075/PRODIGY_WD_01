# PRODIGY_WD_01
-------

# Interactive Navigation Menu

This project is a simple HTML webpage that features an interactive navigation menu. The navigation bar is designed to be responsive, sticky, and changes its background color when the user scrolls down the page. The page contains four main sections: Home, Services, About, and Contact.

## Table of Contents
1. [Files Included](#files-included)
2. [HTML Structure](#html-structure)
3. [CSS Styling](#css-styling)
4. [JavaScript Functionality](#javascript-functionality)
5. [How to Use](#how-to-use)
6. [Customization](#customization)
7. [Notes](#notes)

## Files Included

- `index.html`: The main HTML file that contains the structure of the webpage.
- `README.md`: This file, providing an overview of the project.

## HTML Structure

The HTML file is structured into several key sections:

1. **Head Section**:
   - The `head` section includes meta tags for character set and viewport settings.
   - The title of the webpage is set as "Interactive Navigation Menu".
   - The `style` tag is used to include internal CSS that styles the webpage.

2. **Body Section**:
   - A fixed `nav` element is used to create the navigation bar at the top of the page.
   - The `nav` element contains an unordered list (`ul`) with list items (`li`) that represent different sections of the webpage.
   - The `div` element with an `id` of `content` contains four `section` elements, each corresponding to a part of the webpage: Home, Services, About, and Contact.

## CSS Styling

The styling for the webpage is provided internally within a `<style>` tag in the `head` section. Key styles include:

- **Body**: The page uses the 'Times New Roman' font with no margins or padding.
- **Navigation Bar**:
  - Positioned at the top of the page and fixed, allowing it to stay visible while scrolling.
  - The background color changes smoothly when scrolling.
  - The navigation links change color and background when hovered over.
- **Content Sections**:
  - Each section is given a distinct background color and padding to separate them visually.
  - The `padding-top` of the content div ensures the navigation bar does not overlap the content.

## JavaScript Functionality

The JavaScript code, placed at the end of the `body` section, handles the following functionality:

- **Scroll Event**: The `onscroll` event listener checks the scroll position of the window.
  - When the page is scrolled down more than 50 pixels, the `scrolled` class is added to the navigation bar, changing its background color to a darker shade.
  - If the scroll position is less than 50 pixels from the top, the `scrolled` class is removed, reverting the navigation bar to its original color.

## How to Use

1. **Opening the File**: Simply open the `index.html` file in any modern web browser.
2. **Navigation**: Use the navigation menu at the top of the page to scroll to different sections of the website (Home, Services, About, Contact).
3. **Scroll Effect**: Scroll down the page to see the navigation bar change its background color.

## Customization

- **Colors**: You can change the colors of the navigation bar, links, and sections by modifying the CSS in the `<style>` tag.
- **Font**: Change the font family by editing the `font-family` property in the body style.
- **Sections**: Add or remove sections in the content area by adding or removing `<section>` elements within the `div` with `id="content"`.

## Deployment 
 https://ashwinibalaji2075.github.io/PRODIGY_WD_01/
