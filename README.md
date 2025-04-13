<div style="background-color: white; padding-top:10px" align="center">

[![logo](/logo/ohmyfood@2x.svg "logo")](https://thomas-savigner.github.io/ohMyFood/)
</div>

# Ohmyfood - Responsive Website

Ohmyfood, a platform originally from New York for pre-ordering menus from gourmet restaurants, is expanding to Paris. The task is to create the first version of a responsive website based on a mobile graphic mockup. Then, animations must be included to give a first glimpse of the site when it is fully developed and functional.

## Technical Overview

Static and responsive website for the Ohmyfood platform, developed using HTML and Sass. Focuses on CSS animations to enhance the user interface, including a loading spinner, hover effects on buttons and icons, and animated appearances for menu items.

**Technologies:**

*   HTML5
*   CSS3 / Sass (SCSS)

**Key Features:**

*   Responsive design (Mobile-first approach)
*   CSS Animations:
    *   Loading spinner on the homepage
    *   Button hover effects
    *   Progressive heart icon fill on hover
    *   Staggered appearance of menu items
    *   Checkmark icon appearance on menu item hover

## Setup & Installation

1.  Clone the repository: `git clone [<your-repository-url>](https://github.com/thomas-savigner/ohMyFood.git)`
2.  Navigate to the project directory: `cd ohMyFood`
3.  If using Sass for compilation:
    *   Install Sass (if not already installed): `npm install -g sass` (or use a GUI compiler)
    *   Compile Sass to CSS: `sass sass/style.scss css/style.css --watch` (The `--watch` flag automatically recompiles on changes)
4.  Open `index.html` in your web browser.