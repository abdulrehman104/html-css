## UNIVERSAL SELECTOR:

Universal selector represented by "\*" targets all the HTML elements on the page.

```cs
* {
    property : value;
}
```

```html css
<html>
  <head>
    <style>
      * {
        color: purple;
        text-align: center;
      }
    </style>
  </head>

  <body>
    <p>Welcome to</p>
    <h1>codewithabdul</h1>
  </body>
</html>
```

## ELEMENT SELECTOR:

The element selector selects the target element based on the specific type. Suppose you want to underline all the <p> tags; in this case, the element selector will be the best choice.

The syntax of Element Selector is as follows:

```cs
p {
    property : value;
}
```

```html css
<html>
  <head>
    <title>CSS</title>
    <style>
      p {
        text-decoration: underline;
      }
    </style>
  </head>

  <body>
    <h1>codewithabdul</h1>
    <h2>we offer:</h2>
    <p>Python Tutorials - 100 Days of Code</p>
    <p>Ultimate JavaScript Course</p>
    <p>React JS Tutorials For Beginners</p>
  </body>
</html>
```

## ID SELECTOR:

The ID selector targets the elements based on the specific ID. It is written with the hash “#” character followed by the ID name in the style sheet.

The syntax of ID Selector is as follows:

```cs
#ID {
    property : value;
}
```

```html css
<html>
  <head>
    <style>
      #title {
        text-align: center;
        color: red;
      }
    </style>
  </head>

  <body>
    <h1 id="title">codewithabdul</h1>
    <p>I'm a Developer and the founder of codewithabdul.com</p>
  </body>
</html>
```

## CLASS SELECTOR:

The class selector does the same job as the id selector, a class selector helps group various types of elements. Suppose, we want to give a custom style to a specific group of elements. In this case, the class selector is the best option.
It is written with the period “.” character followed by the class name in the style sheet.

The syntax of Class Selector is as follows:

```cs
.class {
    property : value;
}
```

```html css
<html>
  <head>
    <title>CSS</title>
    <style>
      .red {
        color: red;
      }
    </style>
  </head>

  <body>
    <p>This is simple p tag</p>
    <p class="red">This p tag has class red</p>
    <p>This is simple p tag</p>
    <p class="red">This p tag has class red</p>
  </body>
</html>
```

## GROUP SELECTOR:

The group selector is used to minimise the code. Commas "," are used to separate each selector in a grouping. This reduces the number of lines of code. The code also looks clean.

The syntax of Group Selector is as follows:

```cs
div, p, a {
    property : value;
}
```

```html css
<html>
  <head>
    <title>CSS</title>
    <style>
      h1 {
        color: red;
      }

      p,
      a {
        color: purple;
      }
    </style>
  </head>

  <body>
    <h1>codewithabdul</h1>
    <p>This is the p tag</p>
    <a href="#">This is the anchor (a) tag</a>
  </body>
</html>
```
