# CSS Specificity Issue: Unexpected Color Inheritance

This repository demonstrates a common issue in CSS related to specificity and inheritance.  A nested element's style is not overriding the parent's style due to specificity.

## Problem

The `bug.css` file contains CSS code where a nested `<p>` element's color is unexpectedly inheriting from its parent `<div>` element even when a more specific selector is applied.

## Solution

The `bugSolution.css` file demonstrates how to resolve the issue by using more specific selectors or the `!important` flag (though use of `!important` is generally discouraged).

## How to reproduce

1. Clone the repository.
2. Open `bug.html` in a browser.
3. Observe the unexpected color of the paragraph within the div.
4. Compare the results with the updated CSS in `bugSolution.css`.