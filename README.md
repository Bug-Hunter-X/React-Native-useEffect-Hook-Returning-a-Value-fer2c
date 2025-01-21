# React Native useEffect Hook Returning a Value

This repository demonstrates a common error in React Native applications involving the `useEffect` hook and how to fix it.  The error arises when the `useEffect` hook's callback function returns a value other than `undefined` which results in unexpected behavior or warnings.

The `useEffectBug.js` file shows the problematic code where the `useEffect` hook returns a value. The `useEffectSolution.js` file demonstrates the correct implementation, where the callback function doesn't return any value, fixing the issue.

## How to reproduce

1. Clone this repository.
2. Navigate to the repository's directory.
3. Run `npm install` to install the dependencies.
4. Run `npx react-native run-android` or `npx react-native run-ios` to start the app.

Observe the console logs and the warning in the development console (if applicable).