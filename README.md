# Incorrect State Update in React's useEffect Hook with setInterval
This example demonstrates a common issue when using React's `useState` and `useEffect` hooks with `setInterval`.  The problem arises from incorrectly using the previous state value in the `setCount` callback within the `setInterval` function. If the previous state is not used correctly, there might be some unexpected behavior in the state update process.

## Bug
The `bug.js` file shows an incorrect implementation where the state update in the `setInterval` function does not correctly use the previous state. This leads to unexpected behavior where the counter value might not update accurately.

## Solution
The `bugSolution.js` demonstrates the corrected approach which ensures proper state management by always using the previous state in the `setCount` callback. This guarantees accurate and predictable updates.
