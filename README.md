# Natours


## Features

* B.E.M
* Advanced CSS and SASS
* Animations without Javascript
* NPM  Scripts
* Desktop Approach
* Modern CSS Properties but before using them always check [CanIUse](https://caniuse.com/)
* Responsive Grid System


## Implements 7-1 CSS Architecture

```yml
sass/
|
|– abstracts/
|   |– _variables.scss    # Sass Variables
|   |– _functions.scss    # Sass Functions
|   |– _mixins.scss       # Sass Mixins
|   |– _placeholders.scss # Sass Placeholders
|
|– base/
|   |– _reset.scss        # Reset/normalize
|   |– _typography.scss   # Typography rules
|   …                     # Etc.
|
|– components/
|   |– _buttons.scss      # Buttons
|   |– _carousel.scss     # Carousel
|   |– _cover.scss        # Cover
|   |– _dropdown.scss     # Dropdown
|   …                     # Etc.
|
|– layout/
|   |– _navigation.scss   # Navigation
|   |– _grid.scss         # Grid system
|   |– _header.scss       # Header
|   |– _footer.scss       # Footer
|   |– _sidebar.scss      # Sidebar
|   |– _forms.scss        # Forms
|   …                     # Etc.
|
|– pages/
|   |– _home.scss         # Home specific styles
|   |– _contact.scss      # Contact specific styles
|   …                     # Etc.
|
|– themes/
|   |– _theme.scss        # Default theme
|   |– _admin.scss        # Admin theme
|   …                     # Etc.
|
|– vendors/
|   |– _bootstrap.scss    # Bootstrap
|   |– _jquery-ui.scss    # jQuery UI
|   …                     # Etc.
|
`– main.scss              # Main Sass file
```

* Introduction to Sass: variables, nesting, partials, imports, mixins, functions, extends, and more.
* Using Sass in real-world projects: setting global variables, building for reusability, architecting CSS and managing media queries.
* The NPM ecosystem: setting up a development process to compile Sass and automatic browser reload, and creating a build process to concatenate, prefix and compress CSS files.
* Modern responsive design: fluid grids, layout types, flexible images, using media queries to test for different screen widths, pixel densities and touch capabilities.
* Advanced responsive design workflows: mobile-first vs desktop-first strategies, selecting breakpoints, em vs rem units and feature queries to test for browser support.
* Responsive images in HTML and CSS for faster pageloads: resolution switching, density switching, art direction.
* SVG images in HTML and CSS: how and why to use SVG, generating SVG sprites, changing SVG colours in CSS and best practices.
* Videos in HTML and CSS: building a background video effect.
* How to architect and build a simple grid system with floats.  This project uses float layout.
