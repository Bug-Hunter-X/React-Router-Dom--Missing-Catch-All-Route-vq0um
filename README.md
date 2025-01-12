# React Router Dom: Missing Catch-All Route

This repository demonstrates a common error in React Router v6:  unhandled routes resulting in unexpected behavior.

The `App.js` file shows the incorrect implementation where routes are not handled correctly.  Navigating to a non-existent path leads to a blank page or error.

`AppSolution.js` presents the corrected code, using a catch-all route (`/*`) to handle any undefined routes, usually displaying a 404 page or redirecting.