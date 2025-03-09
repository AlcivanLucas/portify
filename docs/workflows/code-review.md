# Code Review Guidelines

## Goals
- Ensure code quality, readability, and maintainability.
- Catch bugs and potential issues before merging code.
- Share knowledge and best practices among the team.

## Code Review Process
1. **Create a Pull Request (PR):**
   - Base branch should be `dev`.
   - Use a clear and concise PR title and description.
   - Add relevant labels and assign reviewers.

2. **Reviewing Code:**
   - Focus on code functionality, readability, and adherence to coding standards.
   - Check for edge cases, error handling, and potential bugs.
   - Verify that all tests are passing and sufficient test coverage is provided.

3. **Providing Feedback:**
   - Be constructive and specific when giving feedback.
   - Suggest improvements and provide code examples if needed.
   - Avoid vague comments like "fix this"; instead, explain why it needs fixing.

4. **Addressing Feedback:**
   - Respond to comments and make necessary changes.
   - Mark comments as resolved only when the issue is addressed.
   - If you disagree with feedback, explain your reasoning clearly.

5. **Approval and Merging:**
   - Once approved, use **Squash and Merge** to maintain a clean commit history.
   - Never merge your own PR without a review, unless it is a critical hotfix.

## Best Practices
- Keep PRs small and focused on a single task or feature.
- Avoid mixing unrelated changes in the same PR.
- Update documentation and add tests as needed.
- Maintain a consistent coding style throughout the codebase.

## Common Review Checklist
- [ ] Does the code follow the project’s coding standards?
- [ ] Are there any potential bugs or edge cases not covered?
- [ ] Is the code easy to read and maintain?
- [ ] Are there sufficient tests, and do they all pass?
- [ ] Has unnecessary or commented-out code been removed?

