# Final

Group 1 FEWD Final Project

## Goals:

Minimum Requirements:

- A Github repository
- A navigation element on each page
- A responsive layout
- Unanimously agreed upon, and consistent page layouts
- A GitHub Pages URL (this should be left until the end of the project)

Optional:

- JavaScript functionality

## Color Theme:

Top of CSS

```
:root {
  --teal: #23a094;
  --pink: #ff90e8;
  --yellow: #ffc900;
  --lavender: #90a8ed;
}
```

Use `var(--color)`; vs hex

## Font Family:

#### Nunito

#### To embed in `<head>` of HTML File:

```
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Nunito:ital,wght@0,200..1000;1,200..1000&display=swap" rel="stylesheet">
```

#### To use in CSS as a class for a variable style:

```
// <uniquifier>: Use a unique and descriptive class name
// <weight>: Use a value from 200 to 1000

.nunito-<uniquifier> {
  font-family: "Nunito", sans-serif;
  font-optical-sizing: auto;
  font-weight: <weight>;
  font-style: normal;
}
```
