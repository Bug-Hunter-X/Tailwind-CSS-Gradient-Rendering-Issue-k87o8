# Tailwind CSS Gradient Rendering Issue

This repository demonstrates an uncommon bug encountered when using Tailwind CSS gradients.  The issue involves unexpected behavior with the `bg-gradient-to-r` utility and specific color combinations.  The gradient may not render correctly or appear distorted.  The `bug.js` file contains the problematic code, while `bugSolution.js` offers a solution.

**Bug Description:**

The gradient defined using `bg-gradient-to-r from-blue-500 to-purple-500` does not render as expected in all browsers and contexts.

**Solution:**

The solution typically involves adjusting the color palette or using a more compatible gradient definition, potentially specifying more gradient stops for smoother transitions.  See `bugSolution.js` for an example.