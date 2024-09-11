# Responsive Personal Portfolio Website

This project is a personal portfolio website with a responsive design, dark/light mode support, and smooth animations. It includes sections like "About", "Skills", "Projects", "Education", and "Contact". The design focuses on modern UI practices using **HTML5**, **CSS3**, and responsive design for various screen sizes.

## Table of Contents
1. [Features](#features)
2. [Technologies Used](#technologies-used)
3. [File Structure](#file-structure)
4. [CSS Breakdown](#css-breakdown)
5. [Customization](#customization)
6. [Contributing](#contributing)

## Features

- **Fixed Navigation Bar**: The header remains fixed at the top while scrolling, providing easy access to navigation links.
- **Smooth Scroll**: Smooth scrolling behavior for anchor links, improving user experience.
- **Hero Section**: A full-screen landing section with a gradient background and a call-to-action button.
- **Animations**: Fade-in animations for sections like About, Skills, and Projects for a dynamic feel.
- **Responsive Design**: Supports mobile devices with responsive layouts and media queries.
- **Light/Dark Theme**: CSS variables allow for easy switching between light and dark themes.
- **Contact Form**: A simple, styled form for users to reach out directly.

## Technologies Used

- **HTML5**
- **CSS3**
- **Keyframe Animations**
- **Flexbox**
- **Media Queries for Responsive Design**

## File Structure

├── main.html 
├──  style.css 
├──  script.js
├── /images │ └── (all images used in the site) 
└── README.md


## CSS Breakdown

### 1. Global Styles
- **Box Sizing**: The `box-sizing: border-box;` rule is applied globally to ensure padding and borders are included within an element's total width and height.
- **Scroll Behavior**: Smooth scrolling is implemented globally using `scroll-behavior: smooth;`.

### 2. Header (Navigation)
- The header has a fixed position and remains on top during scroll.
- The navigation links are styled with no underline and are aligned horizontally on larger screens and vertically on smaller screens.

### 3. Sections (About, Skills, Projects, Education, Contact)
- Each section has padding and uses keyframe animations like `fadeIn` or `fadeInUp` for smooth entry as the user scrolls down.
- The **About Section** includes a centered container with rounded corners and shadow effects.
- The **Skills Section** utilizes flexbox for the skill bars, making the layout responsive.

### 4. Responsive Design
- Media queries adjust the layout for devices with widths under 768px and 480px.
- The navigation and skills layout become vertical for smaller screens, and buttons, fonts, and padding scale accordingly.

### 5. Dark/Light Theme
- The website supports both light and dark modes through the use of CSS variables.
  - Light mode uses a white background and dark text.
  - Dark mode inverts this, using a darker background and lighter text.

## Customization

- To modify the **color theme**, update the CSS variables defined in `:root`.
- To add new sections, create a new `section` tag in the HTML and apply the same animations and styles as existing sections.
- To add new skills or projects, simply add the relevant HTML within the corresponding section (`#skills`, `#projects`).

## Contributing

If you'd like to contribute to this project, feel free to submit a pull request or open an issue on GitHub.

