# Tailwind CSS Specificity Conflict Bug

This repository demonstrates a common issue when using Tailwind CSS: conflicts with global stylesheets that have higher specificity.  The `bug.html` file shows a simple example where Tailwind classes are unexpectedly overridden.

The solution, outlined in `solution.css`, demonstrates how to resolve this either by adjusting the global stylesheet's specificity or using the `!important` flag (although this should be used sparingly).