# Flowbase - Responsive Landing Page

## Project Description

This project is a fully responsive landing page built using **HTML** and **CSS**, created to replicate the design found in the [Flowbase Minimalist Landing Page Figma file](https://www.figma.com/community/file/1405477150071965596). The landing page includes all major sections such as a header with navigation, hero section, features, clients logos, pricing plans, contact form, and footer. The design is clean, minimalist, and optimized for usability and accessibility.

## Features

- Semantic HTML5 markup with accessibility attributes
- Responsive layout using CSS Grid and Flexbox
- Mobile-friendly navigation with toggle menu
- Smooth hover and focus states for interactive elements
- Contact form with client-side validation and user feedback
- External favicon and brand icon usage
- Cross-browser consistent styling with CSS reset
- Responsive breakpoints for mobile, tablet, and desktop
- Client logos horizontally scrollable on smaller screens
- Clean and maintainable CSS with comments and organized structure

## Technologies Used

- HTML5
- CSS3 (Flexbox, Grid, Media Queries)

## Prerequisites

- Any modern web browser (Chrome, Firefox, Edge, Safari)
- Optional: A local development server to serve files (recommended for best experience)

## Installation and Viewing

1. Clone or download the project files to your local machine.
2. Open the `index.html` file directly in your web browser.
3. Alternatively, to serve with a local HTTP server (optional but recommended):
    - If you have Python installed, run:
        - For Python 3.x:
            `python -m http.server 8000`
        - For Python 2.x:
            `python -m SimpleHTTPServer 8000`
    - Then open `http://localhost:8000` in your browser.

## Deployment on Netlify

To deploy the landing page on Netlify, follow these steps:

1. Push your project files to a GitHub repository.
2. Create a free account on [Netlify](https://www.netlify.com) if you don't have one.
3. From the Netlify dashboard, click **"New site from Git"**.
4. Connect your GitHub account and select your repository.
5. Since this is a static site with no build steps, leave the build command empty.
6. Set the publish directory to the root folder (default is fine).
7. Click **"Deploy site"**.
8. After deployment finishes, you will get a live URL to share your landing page.

## Responsiveness

The landing page layout adapts smoothly to different screen sizes:

- **Mobile (320px - 480px):** Vertical stacking of sections, mobile menu toggle, smaller typography.
- **Tablet (481px - 768px):** Two-column grids for features and pricing, adjusted font sizes.
- **Desktop (769px and above):** Full multi-column layout with expanded navigation and larger images.

## Assumptions and Notes

- The contact form does not have a backend; form submission triggers client-side validation and a thank-you alert.
- Icons are sourced from free icon CDNs (Flaticon, Wikimedia Commons SVGs).
- Fonts use system default sans-serif for better performance and consistency.
- The favicon is a free icon from Flaticon matching the brand style.
- Some subtle shadow effects and transitions are added to enhance UI polish.
- The navigation menu toggles on mobile with accessible ARIA attributes.

## Project Structure

