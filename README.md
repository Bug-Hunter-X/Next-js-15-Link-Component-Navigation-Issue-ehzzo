# Next.js 15 Link Component Navigation Issue

This repository demonstrates a bug encountered when using the Next.js 15 `Link` component.  The navigation functionality appears broken, despite correctly defined routes.

## Bug Report
The `Link` component, while seemingly correctly implemented, fails to navigate to the specified pages.  See `bug.js` for the problematic code. This issue seems specific to Next.js 15 and its new App Router.

## Solution
The solution involves ensuring the `Link` component is used within a valid `app` directory structure and verifying the routes are appropriately handled.  The solution code is available in `bugSolution.js`.