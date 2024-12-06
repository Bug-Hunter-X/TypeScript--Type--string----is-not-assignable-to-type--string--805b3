# TypeScript Type Error Bug
This repository demonstrates a common TypeScript type error and its solution.

**Bug:** The `greeter` function expects a single string argument, but an array of strings is passed. This results in a type error.

**Solution:** The solution modifies the `greeter` function to handle either a single string or an array of strings, appropriately concatenating the names.