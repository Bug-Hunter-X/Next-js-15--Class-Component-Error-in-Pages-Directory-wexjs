# Next.js 15 Class Component Issue in Pages Directory

This repository demonstrates a common issue encountered when upgrading to Next.js 13 or later: the use of class components within the `pages` directory.

Next.js 13+ requires function components in the `pages` directory for optimal performance and compatibility.  Using class components will lead to errors or unexpected behavior during the build process or runtime.

## Bug Description

The `bug.js` file shows an example of using a class component in a Next.js app.  This will produce errors when building and running with Next.js 13+.  The error message will vary depending on the specific error and the version of Next.js used.

## Solution

The `bugSolution.js` file demonstrates the correct approach: using a functional component.  This ensures compatibility and improved performance with Next.js 13+.

## Reproduction

1. Clone this repository.
2. Install dependencies: `npm install`
3. Run the development server: `npm run dev`
4. Observe the error (in `bug.js`) or the successful rendering (in `bugSolution.js`).