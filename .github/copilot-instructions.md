- Avoid `else` by using early `return` or new functions.
- Avoid classes unless they implement a shared behaviour or hide a private state.
- Avoid function-wide scopes, particularly `try`/`catch` and `if`. Instead, make a separate function for its inner scope and have its parent handle the conditions and error handlings.
- Avoid nesting by using early `return` or new functions.
- If a block of code is so complex that it has a paragraph to explain it, move it to a separate function.
- If a method does not use `this`, move it outside the class.
- Instead of using `let`, use `const` and make a function that directly gives the correct value.
- Make all interfaces `readonly`.
- Never use `any`.
- Never use `as`.
- Never use `enum`; replace them by objects with a `const` assertion and export its values as a type alias.
- Never use Hungarian notation.
- Never use tuples; replace them by interfaces.
- Prefer passing around the original object such as `Date` and `URL` instead of serializing it.
- Remove comments that are just repeating the next line. The same goes for `@params` and `@returns` in JSDoc.
- When a comment precedes a declaration, turn it to a TSDoc when that makes sense.
