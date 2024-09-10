# docsify simple style

This Docsify theme allows users to dynamically adjust the theme's accent color and brightness using the `--theme-hue` and `--theme-brightness` CSS variables. The theme is designed with a modern, clean aesthetic, offering both light and dark modes that automatically adapt based on the user's system preferences.

This Docsify theme allows users to dynamically adjust the theme's accent color using a single --theme-hue CSS variable. The theme is designed with a modern, clean aesthetic, offering both light and dark modes that automatically adapt based on the user's system preferences.
Key Features:

* Dynamic Accent Color & Brightness: Easily customize the theme's accent color by adjusting the --theme-hue variable and tweak the brightness with the --theme-brightness variable in the CSS. This allows you to personalize the look and feel of your documentation site with minimal effort.
* Light & Dark Modes: The theme supports both light and dark modes, automatically switching based on the user's system settings. Each mode is carefully designed to ensure readability and aesthetic consistency.
* Responsive Design: The theme is fully responsive, ensuring that your documentation looks great on devices of all sizes, from desktops to mobile phones.
* Enhanced Typography and Code Highlighting: The theme includes modern typography and syntax highlighting for code blocks, making your documentation easy to read and visually appealing.

This theme is perfect for users who want a flexible, customizable documentation experience that can be tailored to match their brand or personal style with just a few lines of CSS.

## Include in Docsify

Add to `index.html`

```html
<link rel="stylesheet" href="https://gllmar.github.io/docsify-simple-style/docsify-simple-style.css">
```

## Change the Theme Hue and Brightness

In your docsify `index.html` after loading 

### theme-hue: 0-360
### theme-brightness: 0-100% 

### Example

```html
<!-- Load docsify-simple-style.css -->
<link rel="stylesheet" href="https://gllmar.github.io/docsify-simple-style/docsify-simple-style.css">
<!-- Custom Color and Brightness in index.html -->
<style>
    :root {
        --theme-hue: 280;        /* Adjust the hue value */
        --theme-brightness: 65%; /* Adjust the brightness */
    }
</style>
