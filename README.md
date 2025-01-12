# React useEffect Hook Bug
This repository demonstrates a common bug in React's useEffect hook. The component attempts to update the browser's title based on a count value. However, it only updates the title when the count is greater than zero, leading to an incorrect title when the count is zero.

The `bug.js` file shows the buggy implementation, while `bugSolution.js` provides the corrected code.