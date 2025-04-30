1. values added:  20
2. final result:  20
3. We should avoid using var because it is function-scoped rather than block-scoped, which can lead to unexpected behavior due to hoisting. Instead, use let or const for safer, more predictable code.
4. values added:  20
5. Returns an error because result was declared using let inside the if block, so it is not accessible outside of that block.
6. Returns an error because result was declared as a const, thus stopping line 9 from executing.
7. Nothing will print due to the function exiting because of the prior error.