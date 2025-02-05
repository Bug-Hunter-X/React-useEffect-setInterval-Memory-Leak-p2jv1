# React useEffect setInterval Memory Leak
This example demonstrates a common mistake in React when using `setInterval` within the `useEffect` hook without proper cleanup.  This leads to memory leaks as the interval continues to run even after the component unmounts.

The `bug.js` file contains the faulty code, while `bugSolution.js` provides the corrected version.