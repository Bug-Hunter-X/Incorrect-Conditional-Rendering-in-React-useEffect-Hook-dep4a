# Incorrect Conditional Rendering in React useEffect Hook

This repository demonstrates a common error in React applications involving incorrect conditional rendering logic within the `useEffect` hook.  The component's title only updates when the count is greater than 0, resulting in the title not reflecting the current count when the count is 0.

The `bug.js` file contains the erroneous code.  The corrected version is provided in `bugSolution.js`. The solution ensures that the title is updated regardless of the value of `count`, resolving the issue.
