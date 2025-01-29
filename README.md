# CSS Specificity Conflict with !important

This repository demonstrates a subtle CSS specificity issue involving the `!important` flag.  The issue arises when a selector with higher specificity overrides a rule containing `!important`.

## Bug Description
The `!important` flag in CSS is usually used to override styles. However, its effectiveness is influenced by CSS specificity. This example shows how a more specific selector can override a rule even if it contains the `!important` flag.

## Bug Reproduction
1. Open `bug.css`.
2. Observe the unexpected color of the `.child` element nested within the `.parent` element.

## Solution
The solution involves understanding and adjusting CSS specificity.  The `bugSolution.css` file provides a correct implementation.

## Contributing
Contributions are welcome!