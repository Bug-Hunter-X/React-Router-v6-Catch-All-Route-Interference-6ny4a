# React Router v6 Catch-All Route Issue

This repository demonstrates a common issue encountered when using catch-all routes (`path="/*"`) in React Router v6.  The catch-all route, intended to handle 404 errors, can unexpectedly intercept requests intended for other routes, leading to incorrect rendering or navigation failures.  This is particularly problematic when dealing with nested routes or routes containing optional parameters.

The solution involves carefully ordering routes and possibly using more specific catch-all routes to avoid conflicts.