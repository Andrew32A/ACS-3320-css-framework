# SimplicityCSS - A Minimalist CSS Framework

SimplicityCSS is a minimalist CSS framework designed to simplify web development and provide a clean, modern look to your web projects. This framework offers a set of predefined styles and components that you can easily integrate into your HTML code. Below, you'll find information on how to use SimplicityCSS and its core features.

## Getting Started

To get started with SimplicityCSS, you can follow these steps:

1. Download the CSS File: You can download the SimplicityCSS stylesheet from this repository. Make sure to include it in your project's directory.

2. Link the Stylesheet: In your HTML file, link to the SimplicityCSS stylesheet in the <head> section of your document.

```html
<link rel="stylesheet" href="path/to/simplicity.css" />
```

3. Apply Styles: SimplicityCSS provides a variety of classes for styling your HTML elements. You can apply these classes directly to your HTML elements to achieve the desired styling.

## Core Features

### Reset and Base Styles

- SimplicityCSS includes a reset and base styles to provide a consistent and clean foundation for your web pages.

### Typography

- The framework defines typography styles for headings (h1 to h6), links (a), and basic text formatting elements like strong, em, and abbr.

### Container

- Use the .container class to create a centered content container with a maximum width of 1200px.

### Buttons

- SimplicityCSS offers customizable button styles with hover animations. You can use the .button, .button-danger, and .button-success classes to style your buttons. These buttons have built-in hover effects for a polished look.

### Form Elements

- Form elements such as text inputs, checkboxes, radio buttons, and more are styled using SimplicityCSS. Simply apply the appropriate classes to your form elements to leverage these styles.

### Tables

- Tables are styled to improve readability and aesthetics. The .table class provides a clean table structure.

### Navigation Bar

- The .navbar class helps you create a navigation bar with links that change color on hover.

### Utility Classes

- SimplicityCSS includes utility classes for margin, padding, text alignment, and more. You can use these classes to fine-tune the styling of your elements.

### Responsive Design

- The framework includes media queries for responsive design. Styles adapt to smaller screens to ensure a consistent user experience across devices.

### Example Usage

Here's an example of how you can use SimplicityCSS to style a basic HTML page:

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>My SimplicityCSS Page</title>
    <link rel="stylesheet" href="path/to/simplicity.css" />
  </head>
  <body>
    <header class="navbar">
      <ul>
        <li><a href="#">Home</a></li>
        <li><a href="#">About</a></li>
        <li><a href="#">Services</a></li>
        <li><a href="#">Contact</a></li>
      </ul>
    </header>

    <section class="container">
      <h1>Welcome to SimplicityCSS</h1>
      <p>This is a sample page using the SimplicityCSS framework.</p>
      <button class="button">Learn More</button>
    </section>

    <footer class="page-footer">
      <ul>
        <li><a href="#">Privacy Policy</a></li>
        <li><a href="#">Terms of Service</a></li>
      </ul>
    </footer>
  </body>
</html>
```

## Customization

You can customize the default colors and styles defined in SimplicityCSS by modifying the CSS variables in the :root section of the stylesheet. Adjust these variables to match your project's branding.

```css
:root {
  --color-background: #0f1626;
  --color-background-alt: #1e293b;
  /* Add more custom variables here */
}
```
