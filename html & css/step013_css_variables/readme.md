# Css Variables
CSS variables, also known as CSS custom properties, are entities defined by CSS authors that contain specific values to be reused throughout a document. They are set using custom property notation (e.g., --my-variable-name) and can be referenced and manipulated using the `var()` function in other parts of the CSS.


```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>CSS Variables Example</title>
  <style>
    /* Define CSS variables */
    :root {
      --primary-color: #007bff;
      --secondary-color: #6c757d;
    }

    /* Use CSS variables */
    body {
      background-color: var(--primary-color);
      color: var(--secondary-color);
      font-family: Arial, sans-serif;
    }

    .container {
      padding: 20px;
      border: 2px solid var(--secondary-color);
    }

    /* Changing the value of a CSS variable on hover */
    .container:hover {
      --secondary-color: #28a745;
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>Welcome to CSS Variables Example</h1>
    <p>This is a simple demonstration of CSS variables.</p>
    <p>Hover over this container to see the change in secondary color.</p>
  </div>
</body>
</html>
```

In this example:

- Two CSS variables (`--primary-color` and `--secondary-color`) are defined at the `:root` level.
- These variables are then used to define the `background-color`, `color`, and border `color` properties of the `body` and `.container` elements.
- Additionally, the `--secondary-color` variable is modified on hover over the `.container` element, demonstrating how variables can be dynamically changed using CSS.

CSS variables provide flexibility and maintainability to your stylesheets by allowing you to define values in one place and reuse them throughout your CSS code.
