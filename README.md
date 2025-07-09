# Personal Portfolio Website

This repository contains the complete source code for my personal portfolio website. The website acts as a dynamic and interactive resume. Its primary goal is to provide a comprehensive overview of my skills, projects, and background to potential employers, collaborators, and anyone interested in my work in physics, data science, and software development.

[**View the Live Website Here**](#)

## Project Ideology and Goals

The key goals for this project were:

*   **To Showcase Technical Competency:** To demonstrate proficiency in front-end technologies by building a appealing and functional website.
*   **To Centralize My Work:** To provide a single, accessible location for my key projects, with direct links to live demos and source code repositories.
*   **To Create a Strong First Impression:** To design an engaging user experience that captures interest from the moment a visitor lands on the page.
*   **To Ensure Accessibility and Responsiveness:** To build a site that delivers a seamless experience across all devices.

## Key Features & Section Breakdown

The website is structured as a single-page application to allow for smooth, narrative-style scrolling and easy navigation.

### 1. Dynamic Hero Section
The first thing a visitor sees is a full-screen hero section designed to be visually engaging.

*   **Image Carousel:** A carousel powered by Bootstrap 5 cycles through a series of personal photos. This adds a dynamic and personal touch, offering a glimpse into my life beyond the screen.
*   **Text Overlay:** A semi-transparent overlay ensures that the introductory text is perfectly readable against the background images.
*   **Clear Introduction:** The centered text immediately communicates who I am and what I do, followed by a prominent call-to-action button ("View My Work") that directs users to the projects section.

### 2. Selected Projects Showcase
This section is the heart of the portfolio.

*   **Card-Based Layout:** Projects are presented in a clean, card-based layout using Bootstrap's grid system. This design is scannable and modular.
*   **Concise Descriptions:** Each card provides a succinct summary of the project, including its purpose and the technologies used.
*   **Action-Oriented Links:** Each project includes clear, icon-driven buttons that link to a live demo and the relevant GitHub repository, encouraging visitors to explore my work in more detail.

### 3. "About Me" and Skills Section
This section bridges the gap between my technical work and my personal identity.

*   **Personal Narrative:** A brief, conversational biography provides context for my academic pursuits and career aspirations. It also shares some of my personal interests, like music, to present a more well-rounded profile.
*   **Key Skills Badges:** My technical skills are displayed as Bootstrap badges. This visual treatment makes them easy to scan and digest, providing a quick overview of my capabilities in programming languages, libraries, and tools.

### 4. Responsive Navigation and Footer
The user experience is supported by consistent and intuitive navigation elements.

*   **Fixed-Top Navbar:** The dark-themed navigation bar remains fixed at the top of the viewport as the user scrolls, ensuring that links to all sections are always accessible. It collapses neatly on smaller screens into a hamburger menu.
*   **Comprehensive Footer:** The footer provides direct, icon-based links to my email, GitHub, and LinkedIn profiles, making it easy for visitors to connect with me.

## Technology Stack

This website was built using a curated set of modern and widely-adopted front-end technologies.

*   **HTML5:** Used for the semantic structure and content of the website.
*   **CSS3:** A custom stylesheet (`styles.css`) is used for specific design choices, such as the hero overlay, card styling, and color scheme, that go beyond the default Bootstrap framework.
*   **Bootstrap 5.3.3:** This is the core framework for the website's design and layout. It was chosen for its robust, mobile-first grid system and its extensive library of pre-styled components (Navbar, Cards, Buttons, Carousel). Its use significantly accelerated development and ensured a high degree of responsiveness out-of-the-box.
*   **Font Awesome 6.5.1:** Utilized for all icons throughout the site, including the social media links in the footer and the action buttons on the project cards. The use of this library provides scalable, high-quality vector icons that are easily customized with CSS.
*   **JavaScript:** While no custom JavaScript was written, the site leverages the JavaScript plugins included in the `bootstrap.bundle.min.js` file to power interactive components like the navigation bar's toggler and the image carousel.
*   **Hosting:** The website is hosted on GitHub Pages, which provides a simple, fast, and free way to deploy static websites directly from a GitHub repository.
