# Uncommon CSS Bug: Invalid Selector

This repository demonstrates a subtle CSS bug related to an invalid selector. The bug is characterized by a CSS rule that doesn't match any element in the HTML, leading to unexpected styling behavior or no effect at all.  This often happens after refactoring or removing elements from the HTML, but leaving the related CSS intact.

## Bug Description

The CSS file (`bug.css`) contains an invalid selector.  The selector `'.invalid-selector'` does not exist in the corresponding HTML file.

## Solution

The solution is to either remove the invalid selector or update the selector to correctly target the intended HTML element. The solution is provided in `bugSolution.css`.