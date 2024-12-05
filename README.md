# React 19 Hook Issue in Nested Components

This repository demonstrates a subtle bug in React 19 related to the use of new hooks like `useTransition` and `useEvent` within nested function components.  The issue arises when these hooks are not used directly within a component that is a direct child of the root component.  The error might manifest as unexpected behavior or rendering issues, without clear error messages.

## Reproduction

1. Clone this repository.
2. Navigate to the project directory: `cd react-19-hook-bug`
3. Install dependencies: `npm install`
4. Run the development server: `npm start`

Observe the unexpected behavior in the application.  The solution demonstrates a way to resolve this.