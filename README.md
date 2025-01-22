# Unexpected Behavior with CSS `calc()`

This repository demonstrates an uncommon issue related to the `calc()` function in CSS.  Inconsistent units or incorrect operator precedence within `calc()` can result in unexpected rendering of elements.  The `bug.css` file showcases the problem, and `bugSolution.css` offers a corrected version.

**Problem:** The original CSS code uses `calc()` to determine the width of an element, but due to unit inconsistencies or operator precedence, the result is not what's intended. 

**Solution:** The solution involves ensuring consistent units in the calculation and clarifying operator precedence using parentheses where needed.