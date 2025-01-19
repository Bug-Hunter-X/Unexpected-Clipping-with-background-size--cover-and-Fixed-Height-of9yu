# CSS background-size: cover; Issue
This repository demonstrates an uncommon issue encountered when using `background-size: cover;` in CSS.  When a container element has a fixed height, the background image might not cover the entire container as expected, sometimes leading to clipping or other unexpected display behaviors. The problem seems to be related to how the browser calculates the aspect ratio and applies the `cover` property in combination with a defined height.

## Bug Report
The `bug.css` file contains the CSS code exhibiting the problem.  The background image is not covering the div as intended. 

## Solution
The `bugSolution.css` file provides a solution to address the issue, offering a more robust approach to handling background image scaling.