# Tier 2. Module 1. Homework 3 - Decorative effects. Animation

* Create repository `goit-markup-hw-04`.
* Clone the created repository and copy the files of previous work to it.
* Complete the markup and layout of the page [**homework #4**](https://www.figma.com/file/wuEpGhwCepGCOUw7mZFRac/Web-Studio-(Version-5.0)?type=design&node-id=297016-823&mode=design&t=HqslgV0OjDOknzIj-0).
* Set up `GitHub Pages` and add a link to the live page in the `About` section of the GitHub repository.

## Acceptance criteria

### Project

`"A1"` In the root of the project there is an `images` folder with images.

`"A2"` All vector images (icons) are collected in the `icons.svg` SVG sprite, which is located in the `images` folder.

`"A3"` All vector images are optimized.

`"A4"` At the root of the project there is a `css` folder with a style file.

`"A5"` All styles are written in one `styles.css` file, which is located in the `css` folder.

`"A6"` File names do not contain capital letters, spaces and transliteration. The names contain only English letters and words.

`"A7"` Source code formatted with `Prettier`.

`"A8"` All images and textual content are taken from the layout.

`"A9"` Connected style normalizer [modern-normalize](<https://cdnjs.com/libraries/modern-normalize>).

`"A10"` The code is written in accordance with the [**instructions**](https://codeguide.co/).

### Markup

`"B1"` Vector graphics in `svg` format are used for all icons.

`"B2"` SVG icons exported correctly. When exporting, the "group" is selected, not the vector itself.

`"B3"` All icons from the SVG sprite are added to HTML using the `<svg>` and `<use>` tags.

`"B4"` Added icons to the benefits section (an untitled section with a list of benefits over `Our Team`).

`"B5"` Social media icons have been added to the `Our Team` section.

`"B6"` Added social network icons in the footer.

`"B7"` Completed HTML markup of all layout elements.

`"B8"` Tags are used according to their semantic content.

### Design

`"C1"` A large image with a blackout effect (below the header) is made as a background. A multi-layer background with a gradient is used for darkening.

`"C2"` The background image in the block under the header does not stretch wider than its original size of `1440px`.

`"C3"` Cards in the `Our Team` section have a permanent shadow effect.

`"C4"` The cards in the `Our Portfolio` section have a hover shadow effect anywhere on the card.

`"C5"` When hovering or focusing, the icons should go into the active state - change color, if this is indicated in the layout.

`"C6"` Transitions are made for all hover and focus effects (color, background, shadow). Time - `250ms`, time distribution function - `cubic-bezier(0.4, 0, 0.2, 1)`.

`"C7"` Animated properties are clearly indicated in transitions. There is no `all` value anywhere.

`"C8"` In the main navigation, with the help of the `::after` pseudo-element, the link of the current page (on which the user is currently located) is underlined.

`"C9"` Text overlay on the cards of the `Our Portfolio` section appears on hover anywhere on the card.

`"C10"` The blue overlay in the cards of the `Our Portfolio` section comes out from the bottom.

`"C11"` Pseudo-elements have no text content in the `content` property. They are used exclusively for decorative purposes.
