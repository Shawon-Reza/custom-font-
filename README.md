# Add_Custom_fonts
# index.css


```jsx
@font-face {
    font-family: 'customfont';
    src: url('./assets/fonts/SpaceGrotesk-Regular.ttf') format('truetype');
    font-weight: 400;
    font-style: normal;
    font-display: swap;
}

/*  Set custom font in overall content......... */
:root {
    --font-customfont: 'customfont', ui-sans-serif, system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial;
}

body {
    font-family: var(--font-customfont);
}

```
