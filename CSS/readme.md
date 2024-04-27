# CSS (Cascading Style Sheets) Documentation

## Introduction

`CSS` (Cascading Style Sheets) is a language used for styling web documents written in HTML and XML. It allows you to control the visual presentation of elements on a webpage, including layout, colors, fonts, and more.

## Syntax

## Selector

`Selectors` are used to target HTML elements that you want to style. There are different types of selectors:

-    Element Selector: Targets all instances of a specific HTML element. Example: p targets all paragraphs.
-    Class Selector: Targets elements with a specific class attribute. Example: .my-class targets elements with class="my-class".
-    ID Selector: Targets a single element with a specific ID attribute. Example: #my-id targets the element with id="my-id".
-    Attribute Selector: Targets elements based on their attributes. Example: [type="text"] targets input elements with type="text".

## Declaration Block

A declaration block consists of one or more declarations enclosed in curly braces {}. Each declaration includes a property and its corresponding value.

Example:

```css

.selector {
  property1: value1;
  property2: value2;
}
```

## Property and Value

CSS properties define the aspects of an element that you want to style, such as color, font size, margin, etc. Each property is followed by a colon : and its value.

Example:

```css

.selector {
  color: red;
  font-size: 16px;
}
```

## Comments

You can add comments in CSS using /* */. Comments are ignored by browsers and are useful for documenting your code.

Example:

```css

/* This is a comment */
.selector {
  /* This property sets the background color */
  background-color: blue;
}
```

## Key Concepts

## Box Model

The CSS box model describes how elements are rendered on a webpage. It consists of the content area, padding, border, and margin.

-    Content: The actual content of the element, such as text or images.
-    Padding: Space between the content and the element's border.
-    Border: The border surrounding the padding.
-    Margin: Space outside the border, separating elements.

## Flexbox

`Flexbox` is a layout model that makes it easier to design flexible and responsive layouts. It provides properties for distributing space, aligning items, and controlling the layout direction.

Example:

```css

.container {
  display: flex;
  justify-content: center; /* Horizontally center items */
  align-items: center; /* Vertically center items */
}
```

## Grid Layout

CSS Grid Layout is a powerful layout system that allows you to create complex grid-based designs. It provides properties for defining rows, columns, and the placement of items within the grid.

Example:

```css

.grid-container {
  display: grid;
  grid-template-columns: 1fr 2fr; /* Two columns with flexible widths */
  grid-gap: 10px; /* Gap between grid items */
}
```

## Units

CSS supports various units for specifying sizes and distances:

-    Pixels (px): Absolute unit, fixed size on screen.
-    Percentages (%): Relative to the parent element's size.
-    Em (em): Relative to the font-size of the element.
-    Rem (rem): Relative to the font-size of the root element.
-    Viewport units (vw, vh, vmin, vmax): Relative to the viewport size.

Example:

```css

.selector {
  width: 200px;
  font-size: 1.2em;
  margin-bottom: 10%;
}
```

## Colors

You can specify colors in CSS using various formats:

-    Keyword: Names like red, blue, etc.
-    Hexadecimal: Hex codes like #ff0000 (red).
-    RGB: RGB values like rgb(255, 0, 0) (red).
-    RGBA: RGB values with alpha transparency like rgba(255, 0, 0, 0.5).

Example:

```css

.selector {
  color: red;
  background-color: #00ff00;
}
```

