# Personal Portfolio Website Documentation

This documentation provides an overview of the HTML and CSS code for a personal portfolio website.

## HTML Code

The HTML code represents the structure and content of the website. Here are the key sections of the code:

- The `<head>` section includes meta tags for defining the character encoding, viewport settings, and page title. It also links to external stylesheets and sets the favicon.

- The `<body>` section contains the main content of the website. It includes sections such as the header, portfolio, services, and footer.

- The header section displays the logo, name, and contact information. It also includes a dark mode toggle button.

- The portfolio section showcases the tools used and current projects.

- The services section highlights the services provided.

- The footer section displays the copyright information.

## CSS Code

The CSS code defines the styles and appearance of the website. Here are some key styles used in the code:

- Custom CSS variables are defined in the `:root` selector to set color and font-related properties.

- The `darkmode` class is applied to the body element to enable dark mode.

- Various sections of the website, such as header, tools, projects, services, and footer, are styled using CSS selectors.

- Text styles, link styles, and responsive styles for different screen sizes are also defined in the CSS code.

## Dark Mode Toggle Functionality

The dark mode toggle functionality is implemented using JavaScript. The `darkmode.js` file handles the enable and disable functionality based on user interaction with the toggle button. When the button is clicked, the `enableDarkMode` or `disableDarkMode` function is called, which adds or removes the `darkmode` class from the body element and updates the `darkMode` setting in the `localStorage`.

## Usage

To use this website template:

1. Replace the content and images in the HTML code with your own information.

2. Customize the CSS styles to match your desired design.

3. Include the `darkmode.js` file in your project to enable the dark mode toggle functionality.

4. Deploy the website to a hosting provider or web server to make it accessible to visitors.

## Example

Here is an example of how the personal portfolio website can be implemented:

```html
<!DOCTYPE html>
<html>
<head>
  <meta charset="utf-8">
  <meta content="width=device-width, initial-scale=1.0" name="viewport">
  <title>HUSAM's Portfolio</title>
  <link rel="shortcut icon" type="image/png" href="image/favicon.png">
  <link href="main.css" rel="stylesheet">
  <link href="https://fonts.googleapis.com/css?family=Space+Mono" rel="stylesheet">
  <link rel="stylesheet" href="https://unpkg.com/kursor/dist/kursor.css">
</head>
<body>
  <!-- Website content goes here -->
  <script src="darkmode.js"></script>
</body>
</html>
