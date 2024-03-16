Explanation:

We use the useState hook to create state for our stack, initialized as an empty array.
handlePush function prompts the user for a new integer value and then adds it to the stack by creating a new array with the previous contents of the stack along with the new value, and updating the state.
handlePop function removes the top element from the stack by creating a new array with one less element than the current stack and copying all elements except the last one into it, and then updating the state.
The contents of the stack are displayed using the map function to iterate over the stack array and render each value.
