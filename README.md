# Reset.css

Reset.css is a custom CSS file designed to reset the default styles of HTML elements, providing a consistent starting point for building web projects across different browsers.

## Features

- **Universal Reset**: Resets margin, padding, and border for all elements to ensure a consistent baseline.
- **Typography Reset**: Resets font properties for common text elements.
- **List Styling**: Removes default list styles.
- **Quote Styling**: Removes default quote styles for blockquotes and quotes.
- **Table Styling**: Ensures consistent table layout.

## Code

The following CSS code is included in the reset file:

```css
html, body, div, span, applet, object, iframe,
h1, h2, h3, h4, h5, h6, p, blockquote, pre,
a, abbr, acronym, address, big, cite, code,
del, dfn, em, img, ins, kbd, q, s, samp,
small, strike, strong, sub, sup, tt, var,
b, u, i, center,
dl, dt, dd, ol, ul, li,
fieldset, form, label, legend,
table, caption, tbody, tfoot, thead, tr, th, td,
article, aside, canvas, details, embed, 
figure, figcaption, footer, header, hgroup, 
menu, nav, output, ruby, section, summary,
time, mark, audio, video {
	margin: 0;
	padding: 0;
	border: 0;
	font-size: 100%;
	font: inherit;
	vertical-align: baseline;
}
/* HTML5 display-role reset for older browsers */
article, aside, details, figcaption, figure, 
footer, header, hgroup, menu, nav, section {
	display: block;
}
body {
	line-height: 1;
}
ol, ul {
	list-style: none;
}
blockquote, q {
	quotes: none;
}
blockquote:before, blockquote:after,
q:before, q:after {
	content: '';
	content: none;
}
table {
	border-collapse: collapse;
	border-spacing: 0;
}
```

# Installation
To use Reset.css in your project, you can either copy the reset.css file into your project directory or import it from your CSS/SCSS files.

# Download and Include
 1. Download the reset.css file and place it in your project directory.
 2. Include the CSS file in your HTML file:
 ```html
 <link rel="stylesheet" href="path/to/reset.css">
 ```

# Import in SCSS
If you're using SCSS, you can import the reset.css file directly:
```scss
@import 'path/to/reset.css';
```
# Usage
Reset.css is intended to be used at the beginning of your CSS file to provide a consistent base for your styles. It should be included before any other custom styles or frameworks.

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Project</title>
  <link rel="stylesheet" href="path/to/reset.css">
  <link rel="stylesheet" href="path/to/custom-styles.css">
</head>
<body>
  <!-- Your content here -->
</body>
</html>
````

# Customization
Feel free to customize the styles in reset.css to fit the needs of your project. You can add, modify, or remove styles as necessary.

# Contributing
If you find any issues or have suggestions for improvements, please feel free to create a pull request or open an issue in the repository.

# License
Reset.css is open-source and released under the MIT License. See the LICENSE file for more information.