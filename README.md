# Accessibility Dialog

## Features

- The Accessibility Dialog is a stand-alone Web Component that can be inserted into any project by following a few steps (see How to Use section below).
- Once the Accessibility Dialog is set up, a user can easily adjust the website they are visiting, with the aim of increasing the usability of the site for people with disabilities.

## How to Use

### This repository contains three files:

1. `accessibilityDialog.webc.js`
2. `accessibilityDialog.html`
3. `ally-dialog-stylesheet.css`

### To integrate the accessibility dialog into your project:

1. Add the accessibililty dialog Web Component (`accessibilityDialog.webc.js`) into your project's repository (probably in a "Components" directory).
2. Include the the Web Component into your `index.html` (or equivalent .html file), i.e. `<script src="../components/AccessibilityDialog/accessibilityDialog.webc.js"></script>`.
3. Add the accessibility dialog button into your HTML by using the markup contained in `accessibilityDialog.html` (style as needed to fit project).
4. Lastly, ensure that you have linked the accessibility dialog stylesheet (`ally-dialog-stylesheet.css`) to your project.

**Note: The most current version of the accessibility dialog still contains some Tailwind style classes, so the styling of the actual dialog might look incorrect (though the functionality should still work) if you are not using Tailwind. This is to be fixed shortly (see To Do section).**

## To Do

- [ ] Remove all tailiwind or bootstrap classes
- [ ] Finish baseline (generic) styling
