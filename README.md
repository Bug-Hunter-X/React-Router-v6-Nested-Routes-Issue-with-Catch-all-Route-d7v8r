# React Router v6 Nested Routes Bug

This repository demonstrates a common issue with nested routes in React Router v6 when using a catch-all route (`/*`).  The catch-all route incorrectly overrides nested route matches.

## Bug Description
The provided `App.js` shows how a nested route is overshadowed by the catch-all route.  This should not happen.  The solution demonstrates the correct implementation.

## Setup
1. Clone this repository.
2. Run `npm install`.
3. Run `npm start`.

## Solution
The solution is provided in `AppSolution.js`. It uses the `useLocation` hook in a custom component to correctly handle nested routes and avoid conflicts with the catch-all route.