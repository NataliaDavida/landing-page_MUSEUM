# Museum Landing Page

## Introduction
Welcome to the **Museum Landing Page** project, developed in strict accordance with a professional Figma design. This is a modern, single-page website created to showcase a museum's identity, including current exhibitions, upcoming events, and essential visitor information. 

The main goal of this project was to build fully accessible user interface using modern frontend technologies and structural methodologies.

## Key Features
* **Responsive Layout:** Smooth adaptation across mobile (>320px), tablet ($\ge$ 768px), and desktop ($\ge$ 1280px) devices.
* **Header with hamburger menu:** Provides a navigable interface that adapts to different screen sizes.
* **Exhibitions and Events Sections:** Features blocks for current exhibitions and events, with interactive elements and detailed information.
* **News:** A block for announcements and blog posts, featuring responsive image variants based on category modifications.
* **Footer** Contains links to social media, contact information, and additional resources.

## Architecture & Technologies Used
* **HTML5:** Semantic markup ensuring document structure and web accessibility.
* **Strict BEM Methodology:** Advanced CSS architecture utilizing modular Block-Element-Modifier nesting to achieve highly clean and maintainable style sheets.
* **Sass (SCSS):** Advanced styling with a modular architecture (split into `_vars.scss`, `_mixins.scss`, and component-based files).
* **Git & GitHub:** Used for meticulous version control and deployment management.

## Challenges & Learning Outcomes
As this was my first experience with creating a comprehensive landing page for a museum, several challenges emerged throughout the development process. One notable challenge was implementing a fully responsive design that accurately reflects the Figma mockups.

### 1. Advanced Responsive Grid & Layouts
Managing complex layouts across diverse screen sizes required a deep dive into CSS Grid and Flexbox. Overcoming layout challenges—such as preventing overlapping elements on mobile devices, mastering grid auto-placement, and handling responsive scaling—significantly enhanced my understanding of building robust UI structures.

### 2. Vertical Spacing & Margin Collapse Debugging
Implementing consistent vertical spacing between multi-layered sections initially caused unexpected layout shifts due to CSS margin collapsing. This hurdle was solved by refactoring component constraints to use inner padding systems and creating isolated layouts, which provided stable, predictable positioning.

### 3. State-Driven Hamburger Menu Integration
Developing a seamless mobile navigation experience posed technical difficulties in coordinating styles and logic. Ensuring that the hamburger menu was both highly functional and aesthetically pleasing required synchronizing JavaScript for active state interactions with CSS transitions for smooth visual effects.

## Technical Requirements
To install and run this project locally, you will need:
* **Node.js** (version 14.x or newer)
* **NPM** (version 6.x or newer)

## Installation & Setup

1. **Clone the repository:**
   
   ```bash
   git clone https://github.com/NataliaDavida/landin-page_Museum.git

3. **Install project dependencies:
   
    ```bash
    npm install

5. **Start the local development server:**
   
    ```bash
    npm start

## Project Links
* **Live Demo:** [DEMO LINK](https://nataliadavida.github.io/landing-page_MUSEUM/)
* **Figma Design:** [Link to Figma File](https://www.figma.com/file/HL3XGt5ZatvJoYBhOaWY5x/museum-prototype?node-id=323%3A1957)


