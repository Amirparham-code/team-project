# Team Project — Git & Pull Request Practice

A course practice repository for the **Term 4, Session 1 pull request exercise**.

**Status: learning exercise.** This repository demonstrates a small GitHub collaboration workflow, not a full application or a client product.

## Current main branch

- `buggy.js` defines `add(a, b)` and exports it with CommonJS.
- `README.md` records the purpose and scope of the exercise.

Despite its filename, `buggy.js` currently returns `a + b`. The function does not perform input validation; JavaScript's normal addition and string-concatenation rules apply.

## Explore the function

With Node.js installed, run this from the repository directory:

```sh
node -e "const add = require('./buggy.js'); console.log(add(2, 3))"
```

For numeric inputs `2` and `3`, the function returns `5`. No dependencies, environment variables or package installation are required by the current source.

There is no package manifest, automated test suite, deployed demo or application UI on the current main branch. This documentation update did not execute the example.

## Learning focus

Branches, focused commits, pull requests and code review. Existing pull requests remain part of the course history.
