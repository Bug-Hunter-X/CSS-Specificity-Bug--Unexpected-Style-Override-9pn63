# CSS Specificity Bug

This repository demonstrates a common CSS bug related to specificity.  A more specific selector unintentionally overrides a more general selector, leading to unexpected styling changes. The `bug.css` file shows the problematic code, and `bugSolution.css` provides a possible solution.

## Problem

The original CSS attempts to style all paragraph elements blue. However, a more specific selector (targeting a paragraph within a specific div) overrides this style with a red color, potentially affecting other paragraph elements unexpectedly. 

## Solution

The solution involves carefully considering CSS specificity and potentially using more general selectors or adjusting class names to ensure intended styles are applied correctly.