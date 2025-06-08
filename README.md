# CSS Restaurant

## Constraints
As a challenge, responsiveness is enforced using only basic CSS (float and media queries, neither Flexbox nor Grid) and no JavaScript.

## UX practices
- Responsiveness is enforced in all three pages. The elements are stacked in mobile view (including the menu options), but change position as the viewport's horizontal dimension increases
- All images are responsive
- As the viewport's horizontal dimension becomes larger, page content is centered between equal-sized margins. Said margins increase their size based on viewport width 
- The menu cards are displayed in three different ways:
    - Mobile view: Stacked, with each image occupying the full width available
    - Tablet view: List view, with each image floating on the right
    - Desktop view: Grid view, with two cards per row
- In tablet view, the image near the contact form is responsive in width, but keeps constant height to not occuppy too much viewport space
- In big desktop view, the form labels align with their respective inputs

## Code practices
The following practices applied to the project improve code readability and maintainability:
- The division of CSS code into five different files:
    - `variables.css`. CSS variables
    - `styles.css`. Code that is common to all three pages. Notice that, since it does not refer to any specific page, it does not include id selectors
    - `home.css`, `menu.css`, `contact.css`. CSS specific to each one of the pages
- CSS variables are used for colours and fonts


## Tools
CSS3 / HTML5

## Author:
Arturo Mora-Rioja
