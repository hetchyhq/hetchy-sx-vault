# Hetchy Delivery

Use this workflow when completing Hetchy work inside a Daytona sandbox.

Start by reading the repository's existing structure and local instructions before editing. Keep changes focused on the requested outcome, preserve unrelated work, and prefer the project's established patterns over new abstractions.

For code changes, update or add tests in proportion to the risk. Run the narrowest useful verification first, then broaden when the change touches shared behavior. If a command cannot run in the sandbox, capture the exact failure and explain the remaining risk in the PR body.

When opening the PR, include the implementation summary, verification evidence, and any compatibility or migration notes needed by a reviewer.
