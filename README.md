# CSS Specificity Bug

This repository demonstrates a common issue encountered in CSS: unexpected style overrides due to CSS specificity.  The `bug.css` file contains the problematic code.  The `bugSolution.css` demonstrates a solution.  The problem arises because a more specific selector unintentionally overrides a less-specific one, despite the order of declaration in the stylesheet.  This can lead to unpredictable styling behaviors, especially when working with complex CSS and nested selectors. 

The solution shows how to understand and avoid these issues through careful use of selectors and organization.

## How to Reproduce

1.  Clone the repository.
2.  Open the HTML file (not provided in this JSON, but should show the impact of specificity).
3. Observe the unexpected styling of the paragraph element(s).