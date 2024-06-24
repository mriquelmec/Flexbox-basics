# Flexbox Layout Example 
This repository contains an example of a simple HTML page demonstrating the use of Flexbox for responsive layouts with columns of varying widths.

## Contents 📁

##### index.html: 
The main HTML file containing the structure of the webpage.
##### styles.css:
The CSS file containing the styles for the rows and columns using Flexbox.

↘
To view the Flexbox layout example, open the index.html file in a web browser. Ensure that the CSS file is in the correct directory as specified.

## Files 📁
##### -index.html
This file contains the HTML structure for the webpage, including three rows with columns of varying widths.

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Flexbox Example</title>
    <link rel="stylesheet" href="styles.css" />
  </head>
  <body>
    <div class="row">
      <div class="col">1/4</div>
      <div class="col">1/4</div>
      <div class="col">1/4</div>
      <div class="col">1/4</div>
    </div>

    <div class="row">
      <div class="col">1/3</div>
      <div class="col col-2">2/3</div>
    </div>

    <div class="row">
      <div class="col col-2">2/5</div>
      <div class="col col-3">3/5</div>
    </div>
  </body>
</html>
```
##### -styles.css
This file contains the CSS styles for the rows and columns using Flexbox. It sets the background color, margin, padding, flex properties, and other styles for the elements.

```css
.row {
  display: flex;
}

.col {
  background-color: rgb(119, 165, 123);
  margin: 5px;
  padding: 10px;
  flex: 1;
  border-radius: 20px;
  box-shadow: rgb(196, 193, 193) 10px 10px 10px;
}

.col-2 {
  flex: 2;
}

.col-3 {
  flex: 3;
}
```
### Directory Structure
Ensure the following directory structure for the files:

```css
project-root/
├── index.html
└── styles.css
```

