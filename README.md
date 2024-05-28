# visualization-linear-regression

This is an npm package that provides visualizations for linear regression. It uses the p5.js library to create interactive visualizations. There are three different JavaScript files, each providing a different visualization. You can switch between them by changing the imported JavaScript file in the `index.html`.

## What the scripts do

1. `sketch0.js`: This script creates a basic linear regression visualization using p5.js.

2. `sketch1.js`: This script enhances the basic visualization by color-coding the data points based on their cost. Data points with higher costs are shown in red, while ones with lower costs are shown in green. As a bonus, the shades of red vary depending on the distance/cost.

3. `sketch2.js`: This script adds interactivity to the visualization. It allows the user to guess the regression line by clicking on the start and end points. Once the line is guessed, their line is shown in blue and the actual line in green. The user is then scored based on the cost difference between their line and the optimal line.

## Installation

To install this package, use the following npm command:

```bash
npm i visualization-linear-regression
```

## Usage

After installing the package, you can use it in your project by importing the desired script in your `index.html` file.

```html
<script src="node_modules/visualization-linear-regression/sketch0.js"></script>
```

Replace `sketch0.js` with `sketch1.js` or `sketch2.js` to use the other visualizations.

## Repository

The source code for this package is available on GitHub: [https://github.com/garvit420/visual-linear-regression](https://github.com/garvit420/visual-linear-regression)
