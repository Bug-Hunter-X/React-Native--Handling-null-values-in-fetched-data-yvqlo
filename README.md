# React Native: Handling Null Values in Fetched Data

This repository demonstrates a common error in React Native applications involving data fetching and null value handling.  The `bug.js` file showcases a component that makes a network request but fails to properly handle potential null values in the received JSON data. This can result in crashes or unexpected UI behavior. The `bugSolution.js` file provides a corrected version that addresses this issue.

## Problem
The `bug.js` example fetches data from an API. However, it doesn't account for scenarios where the API might return null or undefined values for certain fields. Attempting to access properties of a null object will result in an error. 

## Solution
The `bugSolution.js` file demonstrates the solution by adding checks to handle null or undefined values before accessing their properties.  This prevents crashes and ensures more robust error handling.