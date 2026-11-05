# Daily Coding Problem

All 1,853 Daily Coding Problem interview questions (#1–#1857, sent December 2019 – January 2025) in a single Jupyter notebook, with Python solutions added as I work through them.

## What's in the notebook

[`dcp-solutions.ipynb`](dcp-solutions.ipynb) has one section per problem, in number order:

```
### Problem #1
**Easy** · Google · 2019-12-18

#### Problem
Given a list of numbers and a number k, return whether any two numbers from the list add up to k. ...

#### Solution 1: Hash set, one pass
explanation, complexity, then a code cell with asserts

#### Solution 2: Sort, then two pointers
...
```

Each problem shows its difficulty, the company that asked it (where the email named one), and the date it was sent. Problems #530, #840, #935 and #1260 were never received, so they are missing.

## Working in it

- **Solutions.** Put a `#### Solution` caption above a solution. When a problem has more than one, number them: `#### Solution 1: <title>`, `#### Solution 2: <title>`. Solution code ends with `assert`s on the examples, so *Run All* checks every answer.
- **Progress.** The last cell shows the solved count by difficulty, the solved problems, and the next unsolved ones. Run it once per session; after that it refreshes itself every time you run a cell. It reads the saved notebook, so save before expecting a new solution to count. A problem counts as solved once its section contains a code cell.

Requires Python 3 with Jupyter (or VS Code's Jupyter extension); no other packages.

## Credits and license

The problem statements come from the Daily Coding Problem newsletter, which is no longer running; they remain the work of its authors.

The solutions, notes and notebook structure are released into the public domain under the [Unlicense](LICENSE).
