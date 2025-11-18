# Clean Code Principles to Always Follow

## Separation of Concerns
Each module or component should handle a single, specific responsibility. This approach ensures that changes in one area of the code have a minimal impact on others, promoting low coupling and high cohesion. As a result, teams can work on different modules in parallel without creating conflicts.

**Why it matters**: This principle makes the code easier to read, test, and modify.
**Example**: The Model-View-Controller (MVC) design pattern is a classic illustration of this principle.
**Best Practice**: Avoid deeply nested blocks of code; instead, refactor them into separate functions.

## Don't Repeat Yourself (DRY)
The focus of DRY is to reduce redundancy throughout the codebase. This applies not only to code but also to logic, data, and documentation. Centralize any shared logic or configuration to prevent inconsistencies. Where appropriate, use abstraction or utility functions to eliminate duplication.

**Why it matters**: Duplication makes maintenance more difficult and increases the likelihood of errors when requirements change, or if a variable needs to be updated in multiple places.
**Example**: Instead of copying and pasting the same validation logic across multiple modules, define it once in a reusable function.

## Keep it Super Simple (KISS)
This principle emphasizes avoiding unnecessary complexity. Simplicity should be a primary design goal; resist the urge to over-engineer solutions.

*   Prioritize clarity over cleverness.
*   Do not use advanced abstractions or design patterns when a simple conditional or loop will suffice.
*   Write code that a new developer can understand quickly.

**Why it matters**: Simple code is easier to debug, maintain, and evolve. Complexity introduces risk without always adding value, which can slow down development and make future modifications more challenging.
**Example**: Avoid implementing multiple design patterns to solve a simple data flow issue when a straightforward loop and conditional statement would be sufficient.

# Before Making Architectural Decisions
When multiple best practices or design options are valid:
*   Always use `ask_followup_question` to clarify which approach is the best fit for the current situation.
*   Provide context about the trade-offs of each option, including any implications for scalability, maintainability, and performance.
*   The goal is to make an informed choice, not to rigidly adhere to a single approach.

## YAGNI (You Aren't Gonna Need It)
If a feature is not explicitly specified, you aren't going to need it. This principle is a cornerstone of agile development.

# Professional Comments
Code should be self-documenting, and comments should be used sparingly.

*   Use comments to explain the "why," not the "what."
*   Do not write placeholder code unless you are prompted to create a boilerplate or template.
*   Avoid writing comments that explain obvious code.
