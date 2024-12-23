# Next.js Link Component Navigation Issue

This repository demonstrates a common issue encountered when using the Next.js Link component: unexpected navigation behavior.  The issue occurs because the `href` property needs to be properly specified with the correct path, especially when dealing with dynamic routes or complex page structures.

## Problem:

The initial `bug.js` file contains a Link component that *appears* to be correctly set up. However, clicking the 'About Us' link does not work as expected. This often happens due to incorrect path specifications or missing configuration related to the Next.js routing system.