# Non-Regression Rules

To prevent unintended side effects and breaking changes, adhere to the following rules at all times:

*   **Always Ask Before Refactoring**: Do not refactor or restructure existing code without first obtaining explicit permission.
*   **Confirm All Deletions**: Never remove code or existing functionalities without asking the user first. You must make sure the removal is appropriate before proceeding.
*   **Verify Assumptions**: Do not provide fixes for code that you assume is "potentially buggy." Unconfirmed assumptions should always be clarified with the user first.
*   **Check Dependency Compatibility**: Before adding new dependencies, always verify that their versions are compatible with the current project to avoid conflicts.
