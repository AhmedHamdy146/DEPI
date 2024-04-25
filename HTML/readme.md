# HTML Documentation

## `<!DOCTYPE html>`

The `<!DOCTYPE html>` declaration defines the document type and version of HTML being used. It should be placed at the beginning of an HTML document to ensure proper rendering by web browsers.

Example:

```html
<!DOCTYPE html>
<html>
<head>
    <title>Document Title</title>
</head>
<body>
    <h1>Hello, World!</h1>
    <p>This is a paragraph.</p>
</body>
</html>
```

## `<html>`

The `<html>` element represents the root of an HTML document. All other elements must be descendants of this element.

Example:

```html
<html lang="en">
...
</html>
```

## `<head>`

The `<head>` element contains meta-information about the HTML document, such as its title, links to stylesheets, and scripts.

Example:

```html
    <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document Title</title>
    <link rel="stylesheet" href="styles.css">
    <script src="script.js"></script>
    </head>
```

## `<title>`

The `<title>` element sets the title of the HTML document, which is displayed in the browser's title bar or tab.

Example:

```html

    <title>Document Title</title>
```

## `<body>`

The `<body>` element contains the content of the HTML document that is displayed in the browser, such as text, images, links, and other elements.

Example:

```html

    <body>
    <h1>Hello, World!</h1>
    <p>This is a paragraph.</p>
    </body>
```

## Headings `<h1>` to `<h6>`

HTML provides six levels of headings, from `<h1>` to `<h6>`, where `<h1>` is the highest level and `<h6>` is the lowest level.

Example:

```html

    <h1>This is a Heading 1</h1>
    <h2>This is a Heading 2</h2>
    <h3>This is a Heading 3</h3>
    <h4>This is a Heading 4</h4>
    <h5>This is a Heading 5</h5>
    <h6>This is a Heading 6</h6>
```

## `<p>`

The `<p>` element represents a paragraph of text in the HTML document.

Example:

```html

    <p>This is a paragraph.</p>
```

## `<div>`

The `<div>` element is a generic container that is used to group and style content within an HTML document.

Example:

```html

    <div class="container">
    <p>This is inside a div.</p>
    </div>
```

## `<form>`

The `<form>` element is used to create an HTML form for user input, such as text fields, checkboxes, radio buttons, and buttons.

Example:

```html

    <form action="/submit-form" method="post">
    <label for="name">Name:</label>
    <input type="text" id="name" name="name">
    <input type="submit" value="Submit">
    </form>
```
