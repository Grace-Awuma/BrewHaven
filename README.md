This is a two-page coffee shop website developed using SASS/SCSS, incorporating CSS Grid and Flexbox layouts for modern, responsive design. The site is built with several advanced SASS features, allowing for clean, maintainable, and scalable code. Below are the key features and their usage within the project.

Variables
   - Defined in the root of the SCSS file
   - Example: `$primary-color: #4a2c2a;`

Custom Properties
   - Defined in `:root`
   - Example: `--primary-color: #{$primary-color};`

Nesting
   - Used throughout, e.g., in `.nav` and `.menu-item`
   
Interpolation
- Used in custom properties and functions

Placeholder Selectors
- Defined and extended for buttons

Mixins
- Several mixins defined and used, e.g., `@mixin flex-center`


Function
- Custom functions for unit conversion

Extend/Inheritance
- Used for buttons and feature items

Control Directives
- Used in responsive mixin e.g: `@if $breakpoint == sm { ... }`

Maps (additional feature)
- Not explicitly shown, but could be used for breakpoints or color schemes


 CSS Grid Layout

- Used for feature grid and menu items

Flexbox Layout

- Used in navigation, footer, and menu items

Responsive Design

- Implemented using the `responsive` mixin
