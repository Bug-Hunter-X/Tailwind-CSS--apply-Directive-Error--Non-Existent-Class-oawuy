# Tailwind CSS @apply Directive Error: Non-Existent Class

This repository demonstrates a common, yet sometimes tricky-to-debug, error in Tailwind CSS: using the `@apply` directive with a class name that doesn't exist.  This often results in subtle styling issues since Tailwind doesn't always throw an explicit error.

## Reproducing the Bug

1.  Clone this repository.
2.  Inspect the `bug.css` file to see the incorrect `@apply` usage.
3.  Notice how the styles aren't applied as expected.

## Solution

The `bugSolution.css` file demonstrates the fix: ensuring the class name used in `@apply` is correctly defined in your Tailwind configuration or CSS classes.