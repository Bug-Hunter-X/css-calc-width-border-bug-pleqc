# CSS Calc() Width Calculation Error with Borders

This repository demonstrates a common error when using the `calc()` function in CSS to calculate widths while considering borders.  The `bug.css` file contains the problematic CSS, and `bugSolution.css` provides a corrected version.

## Problem

When using `calc()` to determine a width and also applying a border, the border's width isn't automatically accounted for in the calculation. This leads to an unexpected layout, often wider than intended.

## Solution

The solution involves adjusting the `calc()` function to explicitly subtract the border width.  This ensures the final rendered width aligns with the desired calculation.

## Usage

1. Clone the repository
2. Open `bug.html` to see the incorrect layout.
3. Open `bugSolution.html` to see the corrected layout.